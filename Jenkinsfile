pipeline {
	agent { 'any'}
	tools {
		maven 'M3'
	}
	stages {
		stage('checkout') {
			steps {
				git 'https://github.com/effectivejenkins/myProject.git'
			}
		}
	}
}