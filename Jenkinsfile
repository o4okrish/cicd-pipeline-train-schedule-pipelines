pipeline {
  agent any
  stages {
    stage ("Build") {
      steps {
      echo 'running build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts arifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
