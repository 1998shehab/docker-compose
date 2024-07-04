
pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
               sudo docker-compose up -d
            }
        }
    }
}
