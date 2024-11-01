pipeline {
  agent any
  environment {
    APP_NAME = 'test'
  }
  options {
    // Stop the build early in case of compile or test failures
    skipStagesAfterUnstable()
  }
  stages {
    stage('Build') {
      steps {
        echo "Building the app"
      }
    }
    stage('Test') {
      steps {
        echo "Testing the app"
      }
    }
    stage('Deploy') {
      steps {
        echo "Deploying the app"
      }
    }
  }
}
