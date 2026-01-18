pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, I am Harish'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Jenkins Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Acceptence Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
