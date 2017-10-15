pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ls -l'
      }
    }
    stage('teste') {
      steps {
        sh 'pwd'
      }
    }
    stage('deploy') {
      steps {
        input 'Aceita este deploy?'
      }
    }
  }
}