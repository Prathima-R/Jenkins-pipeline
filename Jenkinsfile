pipeline{
	agent any

	tools {
		maven 'maven'
		jdk 'java-11'
	}


	stages{
		stage('git-checkout')
			steps{
		
			}
		}

		stage('compile'){
			steps{
				sh "mvn compile"
			}
		}

		stage('Build'){
			steps{
				sh "mvn package"
			}
		}
	}
}
