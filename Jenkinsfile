pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''sh \'mvn clean\'
sh \'mvn package\'
'''
      }
    }
  }
}