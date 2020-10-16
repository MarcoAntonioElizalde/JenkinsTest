pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Test FireFox') {
      parallel {
        stage('Test FireFox') {
          steps {
            sh 'echo \'Testing firefox\''
          }
        }

        stage('Test Chrome') {
          steps {
            sh 'echo \'Testing Chrome\''
          }
        }

        stage('Test Edge') {
          steps {
            sh 'echo \'Testing edge\''
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy...'
      }
    }

  }
}