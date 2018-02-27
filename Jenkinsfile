pipeline {
  agent any
  stages {
    stage('hjsad') {
      parallel {
        stage('hjsad') {
          steps {
            echo 'sadsfasdf'
          }
        }
        stage('asdfas') {
          steps {
            echo 'adsfasdfas'
          }
        }
        stage('asdfs') {
          steps {
            echo 'sadfasd'
          }
        }
      }
    }
    stage('asd') {
      parallel {
        stage('asd') {
          steps {
            echo 'sdksdk'
          }
        }
        stage('sdfasdf') {
          steps {
            echo 'sdfs'
          }
        }
      }
    }
    stage('sds') {
      steps {
        sh 'echo \'done\''
      }
    }
  }
}