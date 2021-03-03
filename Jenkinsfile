pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        mail(subject: 'test', body: 'test', to: 'reghuran@gmail.com', from: 'ustmaya')
      }
    }

  }
  environment {
    test = 'test'
  }
}