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
         sh 'mvn clean package'
      }
    }

    stage('Test') {
      steps {
        // script
         echo 'Test'
         sh 'mvn test'
        
  
      }
    }
  }

}