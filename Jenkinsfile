pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'python3 myfile.py'
      }
    }

    stage('end') {
      steps {
        echo 'done'
      }
    }

  }
}