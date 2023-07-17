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

    stage('Time') {
      steps {
        timestamps()
      }
    }

    stage('Verify') {
      steps {
        fileExists 'Trigger'
      }
    }

  }
}