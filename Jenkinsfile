pipeline {

    agent any

    stages {
      stage(‘Build’) {
        steps {
          sh 'sudo docker rm $(docker ps -a -q)'
          sh 'sudo /usr/bin/docker-compose up --build'
        }
      }
    }
}


