pipeline {
  agent {
    image 'python:3'
    label 'Python-docker'
  }
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('Build') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}