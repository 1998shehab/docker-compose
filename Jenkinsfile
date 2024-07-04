
pipeline {
    agent any
    
    environment {
        sudo_password = credentials('sudo-password-id') // 20e0e126-18c5-4798-bade-d19103913d6
}        

    stages {
        stage('nginx') {
            steps {        
                sh '''echo ${sudo_password} | sudo -s docker-compose -f /home/yat/Desktop/docker/test1/docker-compose.yml up -d'''
            }
        }
    }
}
