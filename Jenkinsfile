pipeline {
  agent any
  stages {
    stage('pull from github') {
      steps {
        git(url: 'https://github.com/testdev123org/testorg1.git', branch: 'master', credentialsId: 'testdev123', poll: true)
      }
    }
    stage('test') {
      steps {
        echo 'tested'
      }
    }
  }
}