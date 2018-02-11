pipeline {
  agent any
  stages {
    stage('build') {
      steps {
      echo "Hello This is my first pipeline project"
      }
    }
  }
  post {
    always {
      archive 'dist/*.jar'
    }
  }
}
