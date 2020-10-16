pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Test') {
      parallel {
        stage('Test FireFox') {
          steps {
            echo 'Test Fire Fox'
          }
        }

        stage('Test Chrome') {
          steps {
            cho 'Test Chrome'
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
