pipeline {
  agent any
  stages {
    stage('log tool versions') {
      parallel {
        stage('log tool versions') {
          steps {
            sh '''mvn --version
git --version
java --version'''
          }
        }

        stage('Check for pom') {
          steps {
            fileExists 'pom.xml'
          }
        }

      }
    }

  }
}