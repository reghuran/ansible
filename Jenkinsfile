pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        mail(subject: 'test', body: 'test')
      }
    }

  }
  environment {
    test = 'test'
  }
}