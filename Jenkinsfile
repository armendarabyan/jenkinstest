pipeline {
  agent any
  stages {
    stage('connect and pull') {
      steps {
        sh 'ssh -o StrictHostKeyChecking=no ubuntu@52.202.186.125 \'cd ~/jenkinstest && git pull origin master && pwd\''
      }
    }
    stage('node version') {
      steps {
        sh 'ssh -o StrictHostKeyChecking=no ubuntu@52.202.186.125 \'node -v\''
      }
    }
  }
}