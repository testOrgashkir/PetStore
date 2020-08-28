pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test 240240240') {
          steps {
            build 'freestyle 12'
          }
        }
        stage('QA') {
          steps {
            build 'dummy'
            sleep 10
            releases/M145
            powershell 'Start-Sleep -s 1000
          }
        }
      }
    }
  }
}
