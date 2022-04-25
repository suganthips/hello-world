pipeline {
  agent any

  stages('CI') {
    stage('Checkout') {
      steps {
        echo 'Checkout'
        checkout scm
      }
    }

    stage('Build') {
      steps {
        // script
         echo 'Checkout'
        sh 'mvn clean install'
      }
    }

  }

}
