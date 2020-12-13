pipeline {
  agent any
  stages {
    stage('delete space') {
      agent any
      steps {
        echo 'hello world'
      }
    }

    stage('build') {
      steps {
        build 'test'
      }
    }

  }
  environment {
    NAME = 'law'
  }
}