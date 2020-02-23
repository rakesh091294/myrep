pipeline {
  agent any
  stages {
    stage('S1') {
      parallel {
        stage('S1') {
          steps {
            sh 'echo "hello"'
          }
        }

        stage('s1.1') {
          steps {
            sh 'echo" qqwer"'
          }
        }

      }
    }

  }
}