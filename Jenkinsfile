pipeline {
    agent any

    environment {
        SUDO_USERNAME = credentials('name-of-user') // admin 
        SUDO_PASSWORD = credentials('sudo-password-id') // admin
    }

    stages {
        stage('nginx') {
            steps {
                script {
                    sh """
                        echo ${SUDO_PASSWORD} | sudo -S docker-compose -f /home/yat/Desktop/docker/test1/docker-compose.yml up -d
                    """
                }
            }
        }
    }
}


   



        









