pipeline {
  agent any
  stages {
    stage ('') {
      steps {
        echo "Running build automation"
        sh "./gradew build --no-daemon"
        archiveArtifacts artifacts: "dist/trainSchedule.zip"
      }
    }
  }
}
