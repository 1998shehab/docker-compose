
pipeline {
    agent any
    
    environment {
        sudo_username = credentials('name-of-user') // admin
        sudo_password = credentials('sudo-password-id') // admin
}        

    stages {
        stage('nginx') {
            steps {        
                sh """echo ${sudo_username} ${sudo_password} | sudo -s docker-compose -f /home/yat/Desktop/docker/test1/docker-compose.yml up -d"""
            }
        }
    }
}
