pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'This is my pipeline :)'
      }
    }

    stage('Working!') {
      steps {
        echo 'It\'s definitely working! :)'
      }
    }

    stage('New branch') {
      steps {
        echo 'It\'s in a new branch! :)'
      }
    }

    stage('Verify') {
      steps {
        fileExists 'Jenkins'
      }
    }

    stage('') {
      steps {
        sh 'mkdir /home/ubuntu/works '
      }
    }

  }
}