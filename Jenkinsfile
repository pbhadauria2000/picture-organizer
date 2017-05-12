pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            echo 'starting build'
            
          },
          "build_parallel": {
            echo 'starting build_parallel'
            
          }
        )
      }
    }
    stage('finish') {
      steps {
        echo 'finished'
      }
    }
  }
}