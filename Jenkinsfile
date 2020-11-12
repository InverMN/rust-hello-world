pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Building...'
        sh rustc ./main.rs
      }
    }
  }
}