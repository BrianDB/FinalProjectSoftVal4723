pipeline {
  agent any
  stages {
    stage('Build Stage') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }

    stage('Test Stage') {
      steps {
        sh 'mvn test'
        echo 'jyb___ The goal of these tests are to test something. '
        echo 'jyb___ Another test message'
      }
    }

    stage('Deliver') {
      steps {
        echo 'jyb___'
      }
    }

  }
}