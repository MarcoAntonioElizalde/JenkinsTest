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
            echo 'Test Fire Fox'
          }
        }

        stage('Test Chrome') {
          steps {
            echo 'Test Chrome'
          }
        }

        stage('Test Edge') {
          steps {
            echo 'Test Edge'
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