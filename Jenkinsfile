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
cd veggie-list
npm install
npm run build'''
      }
    }

  }
}