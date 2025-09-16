pipeline{
	agent any

	tools {
		maven 'maven'
		jdk 'java-11'
	}


	stages{
		stage('git-checkout'){
			steps{
				git branch: 'verion-1', url: 'https://github.com/ManojKRISHNAPPA/test-1.git'
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
