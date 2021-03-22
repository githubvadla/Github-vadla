pipeline {
 // agent any  is for "where to execute" and agent could be node
   agent any
  //stages "where the work actually happens"
   stages {
       
       stage("build") {
           steps  {
              echo "build the application..."
            }
        }
       
       stage("test") {

           steps  {
              echo "Testing the application..."            
           }
        }
        
       stage("deploy") {
           steps  {
             echo "Deploying the application..."
           }
        }
     }
}
