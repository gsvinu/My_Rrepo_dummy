import groovy.json.JsonOutput
#!/usr/bin/env groovy
import hudson.util.Secret
pipeline{
	agent any
	stages {
		stage('Build Config') {
			steps{
				echo "build stage"
				def props = readProperties file:'config/app.properties'
				echo "${props['First_Name']}"
			}
		}
		stage('Git Checkout') {
			steps {
				echo "git stage"
			}
		}
	}
}	
