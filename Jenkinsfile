pipeline {
	agent any

	stages {
		stage('build') {
			steps {
				sh 'python --version'
			}
			steps {
				sh 'whoami'
			}
		}
		stage('test') {
			steps {
				sh 'flake8 foo.py'
			}
		}
	}
}
