pipeline {
  agent any
  stages {
    stage('verify docker scout') {
      steps {
        sh '''
          docker scout version
          docker version
        '''
      }
    }
  }
}