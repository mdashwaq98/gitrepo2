pipeilne {
	agent {
		node {
			label 'linux-node'
			}
		}
	stage ('clean'){
		tools {
			maven 'maven3.8.6'
			}
		steps {
			sh 'mvn --version'
			sh 'mvn clean'
			}
	}
