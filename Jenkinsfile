pipeline{
  agent any
    stages {
    stage('Maven_install') {
      steps {
        withMaven(maven: 'Maven_Test'){
          sh 'mvn clean install'
        }
      }
    }

  }
}
