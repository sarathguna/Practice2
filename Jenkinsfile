pipeline {
	agent any

	stages {
	    stage('Checkout') {
	        steps {
				checkout scm			        }
		    }
		stage('Build') {
	        steps {
				sh '/home/guna1/Softwares/apache-maven-3.5.4/bin/mvn install'
	        }
		}
		stage('Deployment') {
			steps {
				sh 'echo deployment is succussful!'
			}
		}

	}
}
