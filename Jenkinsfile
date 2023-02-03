pipeline {
	agent { label 'linux-node' }
		
	stages ('clean'){
		tools {
			maven 'maven3.8.6'
			}
		steps {
			sh 'mvn --version'
			sh 'mvn clean'
			}
		steps {
			sh 'mvn --version'
			sh 'mvn package'
			}
		}
	}
