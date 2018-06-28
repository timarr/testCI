pipeline {
  agent any
  stages {
    stage('Print') {
      parallel {
        stage('Print') {
          steps {
            echo 'Hello'
          }
        }
        stage('') {
          steps {
            git(url: 'https://github.com/timarr/testCI.git', branch: 'master')
          }
        }
      }
    }
  }
}