pipeline {
  agent any
  stages {
    stage(‘Error’) {
      steps {
        error “failure test. It’s work”
      }
    }
    stage(‘ItNotWork’) {
      steps {
        echo “is not pass here”
      }
   }
  }
  post {
    success {
      mail to: kiruthikag23@gmail.com, subject: ‘The Pipeline success :(‘
    }
  }
}
