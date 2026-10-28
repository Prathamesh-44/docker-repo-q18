pipeline {
	agent any
	stages {
		stage('Checkout code') {
			steps {
				git branch: 'main',
					url: 'https://github.com/Prathamesh-44/docker-repo-q18.git'
			}
		}
		stage('Build Docker Image') {
			steps {
        sh 'docker build -t myapp:v1 .'
			}
		}
	}
}
