pipeline {
  agent any
  stages {
    stage('Stage') {
      parallel {
        stage('Stage') {
          steps {
            sh 'ls'
          }
        }

        stage('Fireup') {
          steps {
            echo 'Start engine'
          }
        }

      }
    }

  }
}