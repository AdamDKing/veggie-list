pipeline {
  agent any
  stages {
    stage('Test Stage') {
      agent {
        docker {
          image 'angular/ngcontainer:latest'
        }

      }
      steps {
        sh '''echo \'hello world\'
ls'''
      }
    }

  }
}