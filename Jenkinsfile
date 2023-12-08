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

		stage('Integration Test') {
			steps {
				echo "integration test"
			}
		}
	} 
	post {
		always {
			echo 'Ian aweson. I run always '
		}

		success {
			echo 'Irun when you are succesful '
		}
		failure {
			echo 'Irun when you fail '
		}
	}
	
}
