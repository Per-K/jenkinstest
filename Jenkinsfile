pipeline {
  agent any
  stages {
    stage('Check') {
      steps {
        sh '''echo Check
'''
        stash '*.py'
      }
    }
    stage('Test') {
      steps {
        sh 'echo Test'
      }
    }
  }
}