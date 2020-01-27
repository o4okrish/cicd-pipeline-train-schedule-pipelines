pipeline {
  agent any
  stages {
    stage ("Build") {
      steps {
      echo 'running build automation'
      sh './gradlew build --no-daemon'
      archiveArifacts arifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
