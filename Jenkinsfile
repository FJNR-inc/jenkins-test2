pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'python --version'
          }
        }

        stage('') {
          steps {
            echo 'test'
          }
        }

      }
    }

  }
}