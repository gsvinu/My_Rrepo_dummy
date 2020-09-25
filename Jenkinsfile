import groovy.json.JsonOutput
import hudson.util.Secret
pipeline{
	parameters{
		string(First_Name: 'Vinod', description: 'github')
		string(Second_Name: 'Kumar', description: 'github')
	}
	stages {
		stage('Build Config') {
			steps{
				echo "build stage"
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
