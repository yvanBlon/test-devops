pipeline {
  agent any
  stages {
    stage('Stage') {
      parallel {
        stage('Stage') {
          steps {
            sh 'pwd'
          }
        }

        stage('stage1') {
          steps {
            sh 'free -m'
          }
        }

      }
    }

  }
}