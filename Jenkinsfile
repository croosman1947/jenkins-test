pipeline {
  agent any
  stages {
    stage("verify tooling") {
      steps {
        sh '''
          jq --version
          curl --version
          docker compose version
          docker version
          docker info
        '''
      }
    }
  }
}
