pipeline {
  agent any
  stages {
    stage('state test') {
      parallel {
        stage('state test') {
          steps {
            sh 'echo "hello blue"'
          }
        }

        stage('stage parallele') {
          steps {
            sh 'echo "stage parallele"'
          }
        }

      }
    }

  }
}