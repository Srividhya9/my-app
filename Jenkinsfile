pipeline { 
  
   agent any

   stages { 
     stage('Test') { 
        steps { 
           sh 'echo "testing application dev..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application dev..."'
           }
         }
   }
}
