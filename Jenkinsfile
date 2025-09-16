pipeline{
	agent any

	tools {
		maven 'maven'
		jdk 'java-11'
	}


	stages{
		stage('git-checkout'){
			steps{
				git branch: 'main', url: ''
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
