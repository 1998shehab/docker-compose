
pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
               sh 'docker-compose up -d'
            }
        }
    }
}
