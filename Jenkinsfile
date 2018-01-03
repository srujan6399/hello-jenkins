pipeline {
  agent {
    dockerfile {
      filename 'test'
    }
    
  }
  stages {
    stage('docker') {
      steps {
        sh 'echo \'Test\''
      }
    }
  }
}