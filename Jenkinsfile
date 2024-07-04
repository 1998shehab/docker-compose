
pipeline {
    agent any
    
    environment {
        sudo_password = credintials('sudo-password-id') // admin
}        

    stages {
        stage('nginx') {
            steps {        
                sh '''echo ${sudo_password} | sudo docker-compose -f /home/yat/Desktop/docker/test1/docker-compose.yml up -d'''
            }
        }
    }
}
