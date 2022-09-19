pipeline
{
  agent any
  stages
  {
    stage ("The only stage")
    {
      step
      {
        echo "Running the step"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
