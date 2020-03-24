pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'Echo "This is my first Build"'
          }
        }

        stage('Build 2') {
          steps {
            sh 'echo "This is my second Build"'
          }
        }

      }
    }

    stage('Test') {
      steps {
        sh 'echo "The test was completed successfully"'
      }
    }

  }
}