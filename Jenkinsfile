pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'pwd'
          }
        }

        stage('stage2') {
          steps {
            sh 'free -m'
          }
        }

      }
    }

  }
}