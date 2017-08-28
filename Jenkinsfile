pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        parallel(
          "Test": {
            build 'freestyle'
            
          },
          "QA": {
            build 'dummy'
            
          }
        )
      }
    }
  }
}