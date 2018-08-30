pipeline {
  agent none
  stages {
    stage('Publish Event') {
      steps {
        publishEvent simpleEvent('<username>Event')
      }
    }
  }
}