
pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
                docker-compose up -d
            }
        }
    }
}
