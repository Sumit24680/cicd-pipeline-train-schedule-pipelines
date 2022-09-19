pipeline
{
  agent any
  stages
  {
    stage ("The only stage")
    {
      steps
      {
        echo "Running the step"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
