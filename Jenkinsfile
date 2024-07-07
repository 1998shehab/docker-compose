pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
               sh 'whoami'
               sh '  docker compose ps'
               sh '  docker compose -f /home/yat/Desktop/docker/test1/docker-compose.yml/ up -d'
                   
                }
            }
       }
}  


   



        









