pipeline {
	agent any
	triggers {
		 pollSCM ('* * * * *')
	}
	
	stages {
		stage ('Build') {	
			steps {
				echo 'Build stage'
				}
			}
		stage ('Test') {
			steps {
				echo 'Test stage'
				}
			}
		stage ('Deploy') {
			steps {
				echo 'Deploy stage'
				}
			}	
		}		
	}	
