pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        echo 'hello3'
      }
    }
    stage('build') {
      steps {
        build 'micro-service'
      }
    }
  }
}