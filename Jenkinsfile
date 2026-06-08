pipeline {
  agent any
  stages {
    stage('hello-world') {
      steps {
        script {
          echo "Hello world this is first Jenkins pipeline."
        }

        sh 'echo \'testing live edits from blueocean\''
        sh 'echo "Added 3rd step"'
      }
    }

  }
}