pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''date






'''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test step is running'
          }
        }

        stage('test par') {
          steps {
            echo 'test par'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deployed successfully'
        sleep 5
      }
    }

  }
}