pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
      }
    }

    stage('Testing') {
      parallel {
        stage('Testing A') {
          steps {
            echo 'Test A running...'
          }
        }

        stage('Testing B') {
          steps {
            echo 'Test B running...'
          }
        }

      }
    }

  }
}