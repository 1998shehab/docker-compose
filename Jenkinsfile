pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
               sh''' sudo docker compose -f /home/yat/Desktop/docker/test1/docker-compose.yml up -d 
                     sudo docker ps
                     sudo docker compose down .'''
                   
                }
            }
       }
}  


   



        









