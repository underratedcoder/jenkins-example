pipeline {

    agent any
    tools {
        maven 'Maven 3.6.3'
    }
    stages {
        stage('Compile stage') {
            steps {
                bat "mvn clean compile"
        }
    }

         stage('testing stage') {
             steps {
                bat "mvn test"
        }
    }

          stage('deployment stage') {
              steps {
                bat "mvn deploy"
        }
    }

  }

}