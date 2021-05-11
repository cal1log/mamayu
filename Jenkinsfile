pipeline {

    agent any

    stages {
      stage(‘Build’) {
        steps {
          sh 'docker rm $(docker ps -a -f status=exited -q)'
          sh 'sudo /usr/bin/docker-compose up --build'
        }
      }
    }
}


