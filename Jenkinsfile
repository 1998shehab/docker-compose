
pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
                whoami         
                   sh ' sudo docker-compose -f /home/yat/Desktop/docker/test1/docker-compose.yml up -d'
            }
        }
    }
}
