pipeline {
  agent any {
    stage ('Build') {
     step {
      echo 'running build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
     }
  }
}
