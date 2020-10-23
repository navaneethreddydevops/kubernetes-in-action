pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
        echo 'Hello'
      }
    }

    stage('Sleep') {
      steps {
        sleep 10
      }
    }

    stage('Timestamps') {
      steps {
        timestamps() {
          sleep 20
        }

      }
    }

  }
}