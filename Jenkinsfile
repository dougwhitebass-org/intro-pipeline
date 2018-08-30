pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('stage01') {
      steps {
        echo "Howdy ${MY_NAME}!"
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Doug'
    TEST_USER = credentials('test-user')
  }
}