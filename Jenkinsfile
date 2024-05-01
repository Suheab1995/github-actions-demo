pipeline {
  agent any
  stages {
    stage('verify act installation') {
      steps {
        sh 'ls -ll'
        sh 'pwd'
        sh 'ls -ll'
      }
    }
    stage('run the entire pipeline') {
      steps {
        sh 'act'
      }
    }
    stage('view the executive graph') {
      steps {
        sh 'act -l'
      }
    }
  }
}
