pipeline {
	agent any
	
	stages {
		stage('Build') {
			steps {
				echo 'Building..'
			}
		}
		stage('Test') {
			steps {
				echo 'Testing..'
				input "Does the staging environment look ok?"
			}
		}
		stage('Deploy') {
			steps {
				echo 'Deploying ..'
			}
		}
	}
}
