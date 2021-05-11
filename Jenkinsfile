pipeline {

    agent any

    stages {
      stage(‘Build’) {
        steps {
          sh 'sudo /usr/bin/docker-compose up --build'
        }
      }
    }
}
