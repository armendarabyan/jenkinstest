pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''ssh -t -o StrictHostKeyChecking=no  ubuntu@52.202.186.125 pwd
ls
cd ~/jenkinstest
git pull origin master'''
      }
    }
  }
}