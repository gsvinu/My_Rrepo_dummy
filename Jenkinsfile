import groovy.json.JsonOutput
import hudson.util.Secret
pipeline{
	agent any
	stages {
		stage('Build Config') {
			steps{
				script {
					sh """
						echo "Build stage"
					"""
				}
			}
		}
		stage('Git Checkout') {
			steps {
				script {
					sh """
						echo "git stage"
					"""
				}
			}
		}
	}
}	
