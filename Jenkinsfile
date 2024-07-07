pipeline {
    agent any

    environment {
        sudouser= sudo adduser admin
        SUDO_USERNAME = credentials('admin')
        SUDO_PASSWORD = credentials('admin')
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


   



        









