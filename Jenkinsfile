pipeline {
  agent any
  stages {
    stage('Build Stage') {
      steps {
        bat(script: 'mvn -B -DskipTests clean package', encoding: 'UTF-8')
      }
    }

    stage('Test Stage') {
      steps {
        bat(script: 'mvn test', encoding: 'UTF-8')
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