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
			steps{
				sh "ls"
			}
		}
		stage("show readme"){
			steps{
				sh "cat README.md"
			}
		}
	}
}