pipeline{
	agent any
	stages {
		stage('Install Dependencies') {
			steps {
				sh ("./dependencies.sh") 
			}
		}
		stage('perform Sonarqube SAST test') {
			steps {
				sh ("./sonarqube.sh")
			}
		}
		stage('Install Docker') {
			steps {
				sh ("./ansible/DockerInstallScript.sh") 
			}
		}
		stage('Build Test Environment') {
			steps {
			}
		}
		stage('run services and NGINX') {
			steps {
				sh ("./ExecutePlaybook.sh") 
		}
	}
}
