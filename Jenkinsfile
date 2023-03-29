pipeline {
  agent any
  stages {
    stage('python version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('python script') {
      steps {
        sh 'python3 sample.py'
      }
    }
  }
}
