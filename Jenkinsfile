pipeline {
  agent any
  stages {
    stage('hello-world') {
      steps {
        script {
          echo "Hello world this is first Jenkins pipeline."
        }

        sh 'sh "echo \'testing live edits from blueocean\'"'
      }
    }

  }
}