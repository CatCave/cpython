pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh './configure --with-pydebug --enable-shared'
      }
    }

  }
}