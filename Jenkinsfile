// SCRIPTED --> stages are optional

/* node {
	echo "Build"
	echo "Test"
	echo "integration test"
}*/

//DECLARATIVE
pipeline {
	//agent any
	agent {docker {image 'maven:3.6.3'}}
	stages {
		stage('Build') {
			steps {
				sh 'mvn --version'
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
		//changed
	}
	
}
