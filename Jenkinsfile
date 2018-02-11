pipeline {
  agent any
  stages {
    stage('build') {
      steps {
      echo "Hello This is my first pipeline project"
      }
    }
  }
  // this is for post build action and archive artifacts to match with fingerprint
  post {
    always {
      //archiveArtifacts artifacts: 'dist/*.jar', fingerprint: true
      echo "This is for archiveArtifacts fingerprint"
    }
  }
}
