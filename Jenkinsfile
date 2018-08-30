pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('stage01') {
      steps {
        echo "Howdy ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Doug'
  }
}