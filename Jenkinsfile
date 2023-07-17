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

    stage('mkdir') {
      steps {
        sh 'sudo mkdir /home/ubuntu/works '
      }
    }

    stage('adduser') {
      steps {
        sh '''sudo adduser testjenkins --disabled-login 
-y'''
      }
    }

    stage('UserList') {
      steps {
        sh 'sudo cat /etc/passwd file.'
      }
    }

  }
}