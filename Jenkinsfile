pipeline{
	agent any
	stages {
		stage('Install Docker') {
			steps {
				sh ("./ansible/playbook.yaml")
			}
		}
		stage('Run Tests') {
			steps {
			
			}
		}
		stage('Build service-1') {
			steps {
				sh "docker-compose build"
			}
		}
		stage('Push images') {
			steps {
				script {
					docker.withRegistry('https://registry.hub.docker.com', 'docker-hub-credentials'){
				image.push("localhost:8082/service-1")
				image.push("localhost:8082/service-2")
				image.push("localhost:8082/service-3")
				image.push("localhost:8082/service-4")
					}
				}
			}
		}
		stage('Run program') {
			steps {
				sh "docker-compose pull && docker-compose up -d"
			}
		}
	}
}
