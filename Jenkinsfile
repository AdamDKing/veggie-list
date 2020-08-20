pipeline {
  agent any
  stages {
    stage('Test Stage') {
      agent {
        docker {
          image 'node:current-alpine'
        }

      }
      steps {
        sh '''echo \'hello world\'
ls'''
      }
    }

  }
}