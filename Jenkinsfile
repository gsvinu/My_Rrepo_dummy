import groovy.json.JsonOutput
import hudson.util.Secret
pipeline{
	parameters{
		string(First_Name: 'Vinod')
		string(Second_Name: 'Kumar')
	stages {
		stage('Build Config') {
			steps{
				echo "build stage"
				def props = readProperties file:'config/app.properties'
				echo "${params.First_Name}"
			}
		}
		stage('Git Checkout') {
			steps {
				echo "git stage"
			}
		}
	}
}	
