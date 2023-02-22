pipeline { 
     agent any
     tools { 
      maven 'MAVEN_HOME' 
      jdk "jdk-11"
     }
     stages { 
     stage('Clean') { 
     steps {
              sh 'mvn clean' 
              } 
       }  
        
        stage('Test') {
        steps { 
            sh 'mvn test' 
               }                   
                       } 
         stage(' Package') { 
         steps { 
         sh 'mvn package' 
                } 
          }
          }
          }
