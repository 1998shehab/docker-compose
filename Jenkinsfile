pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
               sh''' 
               cd /home/yat/Desktop/docker/test1
               if [ "$(sudo docker ps --filter "name= mongo-db-shehab" --filter "status=running" || "name=mongoexpress-shehab" --filter "status=running" -q)" ]; then
                        echo "Express container is already running."
               else
                        echo "Express container is not running. Starting it up..."
                        docker compose -f docker.compose.yml up  -d
               fi '''
                   
                }
            }
       }
}  


   



        









