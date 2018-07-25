pipeline {
	agent any

	stages {
		stage('build') {
			steps {
				sh 'whoami'
			}
			steps {
				sh 'python --version'
			}
		}
		stage('test') {
			steps {
				sh 'flake8 foo.py'
			}
		}
	}
}
