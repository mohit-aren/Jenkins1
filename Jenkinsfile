pipeline {
  agent any
  stages {
    stage("Build") {
       steps {
          // Just print a Hello, Pipeline to the console
          echo "Hello, Pipeline!"
          // Compile a Java file. This requires JDKconfiguration from Jenkins
          sh "python sample.py"
       }
   }
 } // End of stages
} // En
