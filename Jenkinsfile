pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh 'yarn install'
        sh 'yarn test'
      }
    }
  }
}