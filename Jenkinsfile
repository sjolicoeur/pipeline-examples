pipeline {
  agent any
  stages {
    stage('test 1') {
      steps {
        input(message: 'hello', ok: 'yes', id: '12')
        sh 'echo "hello"'
      }
    }
  }
}