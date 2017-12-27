pipeline {
  agent any
  stages {
    stage('Check') {
      steps {
        sh '''echo Check
'''
        stash(name: 'py-file', includes: '*.py')
      }
    }
    stage('Test') {
      steps {
        sh 'echo Test'
        sh '''python hello.py
'''
      }
    }
  }
}