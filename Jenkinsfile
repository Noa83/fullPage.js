pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'php -v'
      }
    }
  }
  environment {
    FTP_CREDS = 'FtpTestDeploy'
  }
}