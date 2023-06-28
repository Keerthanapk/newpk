pipeline {
    agent any

    stages {
        stage('Maven Version') {
            steps {
               sh 'mvn -v'
            }
        }
        stage('Running Test') {
            steps {
                sh 'mvn clean test'
            }
        }
      }
   }   
