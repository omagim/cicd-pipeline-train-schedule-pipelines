pipeleine {
  agent any
  stages {
  stage {'Build'} {
    steps {
      echo 'Running build automation'
      sh './gradlw build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
   }
  }
}
