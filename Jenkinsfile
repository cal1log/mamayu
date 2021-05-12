pipeline {

    agent any

    stages {
      stage(‘Build’) {
        steps {
          sh 'sudo docker container prune -f'
          sh 'sudo /usr/bin/docker-compose up --build'
        }
      }
    }
}


