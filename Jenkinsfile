currentBuild.displayName= " Online-shopping ----"+currentBuild.number
pipeline
{
    agent any
     environment {
        name = "vijay"
        CUSTOM_VAR = "Hello, Jenkins!"
     }
     stages {
         stage("Welcome"){
             steps{
                 echo "Welcome to Jenkins declearative pipeline"
             }
         }
         stage("Print Env"){
             steps{
                
                  echo "Custom Variable: ${env.CUSTOM_VAR}"
             }
         }
          stage("My Name"){
             steps{
                
                  echo "Name: ${env.name}"
             }
         }
     }
}
