pipeline
{
  agent any

    stages
    {
    
      stage("Build")
      {
        steps
        {
          bat 'javac SamplePrime.java'
          bat 'java -version'
        }
       }
       
       stage('Run')
       {
        steps
        {
          bat 'java SamplePrime'
        }
       }
      }
 }     
