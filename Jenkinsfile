pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'mvn --version'
          }
        }
        stage('Build1') {
          steps {
            sh 'echo "step 1"'
          }
        }
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