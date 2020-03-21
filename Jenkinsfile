pipeline
{
  agent any
  
  stages
  {
    stage ('Build')
    {
      steps 
      {
        echo 'Running build automazzzion'
        sh './gradlw build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }   
}
  
