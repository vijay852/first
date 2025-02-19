pipeline
{
    agent any
     environment {
        name = "vijay"
     }
     stages {
         stage("Welcome"){
             steps{
                 echo "Welcome to Jenkins declearative pipeline"
             }
         }
         stage("Print Env"){
             steps{
                 echo $name
             }
         }
     }
}