
pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
               sh 'sudo docker-compose up -d'
            }
        }
    }
}
