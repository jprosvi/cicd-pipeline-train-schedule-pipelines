pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running build automation by JP'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainShedule.zip'
      }
    }
  }

}
