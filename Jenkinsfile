pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        sh 'echo "This is initialize step"'
      }
    }
    stage('Build') {
      steps {
        echo 'This is Build Stage'
      }
    }
    stage('Dev Delivery') {
      steps {
        echo 'This is delivery to Dev Environment'
      }
    }
    stage('Dev Test ') {
      steps {
        echo 'This is test stage'
      }
    }
  }
  environment {
    author = 'Hari Bawa'
    project = 'Test Project'
  }
}