pipeline {
	agent any
	triggers {
		 cron ('* * * * *')
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
