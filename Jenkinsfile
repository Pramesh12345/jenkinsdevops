pipeline {
  agent any
  stages {
    stage('Build stage') {
      steps {
        build 'maven-pramesh'
      }
    }
    stage('deploy stage') {
      steps {
        build 'herodeploy'
      }
    }
  }
}