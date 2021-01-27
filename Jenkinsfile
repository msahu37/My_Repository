pipeline{
  agent any
      stages{
            stage("build"){
            steps{
              echo 'buiding the application.....'
              }
            }
     
     
            stage("test"){
            steps{
              echo 'testing the application.....'
              }
            }
     
   
            stage("deploy"){
            steps{
              echo 'deploying the application.....'
              }
            }
      }
     post{
     
     always{ echo 'ALWAYS will always execute irrespective of build result.'}
     
     success{ echo 'SUCCESS will execute if the build result is successful.'}
     
     faliure{ echo 'FALIURE will execute if the build result is fail.'}
     }
     
  }
