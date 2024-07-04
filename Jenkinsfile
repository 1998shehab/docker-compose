
pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
               $class: 'Docker-Compose up -d'
            }
        }
    }
}
