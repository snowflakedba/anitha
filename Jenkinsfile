pipeline {
  agent {
    label 'jdk 9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World'
        sh 'java -version'
      }
    }
  }
}