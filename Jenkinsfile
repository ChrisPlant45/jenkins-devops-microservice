// Scripted pipeline - OLD
//node {
//	stage('Build') {
//		echo "Build"
//	}
//	stage('Test') {
//		echo "Test"
//	}
//	stage('Integration Test') {
//		echo "Integration Test"
//	}
//}

// Declarative - NEW
pipeline {
	agent any
	stages {
		stage('Build 1') {
			steps {
				echo 'Build 1'
			}
		}
		stage('Build 2') {
			steps {
				echo 'Build 2'
			}
		}
		stage('Build 3') {
			steps {
				echo 'Build 3'
			}
		}
	} post {
			always {
				echo 'ALWAYS'
			}
			success {
				echo 'SUCCESS'
			}
			failure {
				echo 'FAIL'
			}
	}
}
