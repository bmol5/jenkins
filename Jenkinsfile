pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO BRAYAN"'
      sh '''
        echo "Welcome to B2"
        uname -a
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO mol"'
      sh '''
        echo "This list current dir"
        pwd
        '''
      }
    }
  }
}
