pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn --version'
      }
    }
    stage('Test') {
      steps {
        sh '''echo "test step"
'''
      }
    }
  }
}