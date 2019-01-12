pipeline {
  tools {
    gradle 'gradle'
  }
  agent any
  stages {
    stage('Print') {
      steps {
        echo 'Hii'
        bat 'gradle build'
      }
    }
  }
}
