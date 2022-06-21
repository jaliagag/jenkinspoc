pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo $(uptime)
'''
      }
    }

    stage('deploy') {
      steps {
        sh 'terraform -version'
      }
    }

  }
  environment {
    env = 'poc'
  }
}