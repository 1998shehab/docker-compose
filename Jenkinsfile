
pipeline {
    agent any
    
    environment {
        sudo_password = credentials('sudo-password-id') // admin admin
}        

    stages {
        stage('nginx') {
            steps {        
                sh '''echo ${sudo_password} | sudo docker-compose -f /home/yat/Desktop/docker/test1/docker-compose.yml up -d'''
            }
        }
    }
}
