pipeline {	 
   agent any	 
   stages {     	 
      stage("Compile") {          	 
         steps {               	 
            sh "mvn package"          	 
         }     	 
      }     	 
      stage("Unit test") {          	 
         steps {               	 
            sh "mvn test"          	 
         }     	 
      }	 
   }
}
