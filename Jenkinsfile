pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        echo 'Hello world!'
        sh 'echo "Running on ${hostname}"'
      }
    }

    stage('Stage 2') {
      steps {
        echo 'Sleep for 30 seconds'
        sleep 30
      }
    }

    stage('Stage 3') {
      steps {
        echo 'Done'
      }
    }

  }
}