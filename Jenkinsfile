pipeline {
	agent none
	stages {
		stage ('Build') {
			agent {master}	
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
