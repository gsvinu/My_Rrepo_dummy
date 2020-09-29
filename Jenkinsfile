import groovy.json.JsonOutput
import hudson.util.Secret
pipeline{
	agent any
	stages {
		stage('Build Config') {
			steps{
				script{
					sh """
						echo "build stage"
					"""
				}
			}
		}
		stage('Git Checkout') {
			steps {
				echo "git stage"
			}
		}
		stage('Code Quality'){
			steps{
				echo "Code Quality"
			}
		}
		stage('Code Coverage'){
			steps{
				echo "Code Coverage"
			}
		}
		stage('Deploy'){
			steps{
				echo "Deploy stage"
			}
		}
	}
}	
