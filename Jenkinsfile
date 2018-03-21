pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''ssh -t ubuntu@52.202.186.125
cd jenkinstest
git pull origin master'''
      }
    }
  }
}