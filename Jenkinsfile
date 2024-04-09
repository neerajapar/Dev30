pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo 'Build the application'
      }
      steps {
        echo 'Test'
        test success
      }
    }
  }
} 
