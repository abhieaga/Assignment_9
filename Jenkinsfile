pipeline
{
  agent any
   
  stages
  {
    stages('Build')
    {
      steps
      {
        bat 'javac HelloWorld.java'
        bat  'java --version'
       }
      }
      stage('Run')
      {
        steps
          {
              bat 'java HelloWorld'
           }
         }
       }
  }
