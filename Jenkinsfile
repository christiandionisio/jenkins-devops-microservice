// SCRIPTED --> stages are optional

/* node {
	echo "Build"
	echo "Test"
	echo "integration test"
}*/

//DECLARATIVE
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}

		stage('Test') {
			steps {
				echo "Test"
			}
		}

		stage('Integration TEst') {
			steps {
				echo "integration test"
			}
		}
	}
	
}
