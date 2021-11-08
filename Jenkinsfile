pipeleine{
  agent any
  stages {'Build'} {
    steps {
      echo 'Running build automation'
      sh './gradlw build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
    
  }
}
