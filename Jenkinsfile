
pipeline {
    agent any
    
    environment {
        sudo_password = credentials('sudo-password-id') \\ admin
}        

    stages {
        stage('nginx') {
            steps {        
                sh """echo ${sudo_password} | sudo -s docker-compose -f /home/yat/Desktop/docker/test1/docker-compose.yml up -d"""
            }
        }
    }
}
