pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Starting build project'
        mail(subject: 'Build Failure', body: 'Error message body', to: 'toemail@email.com', from: 'from@email.com')
      }
    }
  }
}