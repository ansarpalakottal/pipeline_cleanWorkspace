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
		stage('Deleting the workspace'){
			steps{
				deleteDir()
			}
		}
		stage('Listing the files after cleanworkspace'){
			steps{
				sh 'ls ./'
			}
		}
	}
}
