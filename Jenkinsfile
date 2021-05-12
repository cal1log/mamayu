pipeline {

    agent any

    stages {
      stage(‘Build’) {
        steps {
          sh 'sudo docker kill $(docker ps -q)'
          sh 'sudo /usr/bin/docker-compose up --build'
        }
      }
    }
}


