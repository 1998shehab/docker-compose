pipeline {
    agent any

    stages {
        stage('nginx') {
            steps {
                script {
                    sh '''
                        cd /home/yat/Desktop/docker/test1
                        if [ "$(sudo docker ps --filter "name=mongo-db-shehab" --filter "status=running" -q)" ] || [ "$(sudo docker ps --filter "name=mongoexpress-shehab" --filter "status=running" -q)" ]; then
                            echo "mongo container is already running."
                        else
                            echo "Express container is not running. Starting it up..."
                            sudo  docker-compose -f docker-compose.yml up -d
                        fi
                    '''
                }
            }
        }
    }
}


   



        









