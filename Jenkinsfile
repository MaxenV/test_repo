pipeline {
	agent any
	
	stages{
		stage("Checkout"){
			steps{
				checkout scm
			}
		}

		stage('Build'){
			steps{
				echo "Buduje"
			}
		}

		stage("show fieles"){
			sh "ls"
		}
		stage("show readme"){
			sh "cat README.md"
		}

	}
}