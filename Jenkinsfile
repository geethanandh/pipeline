pipeline {
  agent any
  triggers { 
        cron('0/5 0 0 ? * * *') 
    }
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World"'
      }
    }
  }
}