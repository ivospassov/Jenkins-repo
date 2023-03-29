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
      parallel {
        stage('Stage 2.1') {
          steps {
            echo 'This is stage 2.1'
          }
        }

        stage('Stage 2.2') {
          steps {
            echo 'This is stage 2.2'
          }
        }

      }
    }

    stage('Stage 3') {
      steps {
        echo 'Done'
      }
    }

  }
}