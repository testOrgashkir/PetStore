pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        parallel(
          "Test": {
            build 'stage1'
            
          },
          "QA": {
            build 'stage2'
            
          }
        )
      }
    }
  }
}