
pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
               $class: 'DockerComposeBuilder'
            }
        }
    }
}
