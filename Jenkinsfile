pipeline {
  agent any
  stages {
    stage('verify docker scout') {
      steps {
        sh '''
          docker --version
          docker scout --version
        '''
      }
    }
  }
}