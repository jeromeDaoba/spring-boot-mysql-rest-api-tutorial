pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            echo 'echo "test"'
          }
        }
        stage('') {
          steps {
            sleep 20
          }
        }
      }
    }
  }
}