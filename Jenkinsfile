#!groovy
pipeline{
	agent any
	stages{
		stage('Creation of File'){
			steps{
				sh 'touch 1.txt'
			}
		}
		stage('Listing the file'){
			steps{
				sh 'ls ./'
			}
		}
	}
}
