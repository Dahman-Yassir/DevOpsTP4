pipeline { 
     agent any
     tools { 
      maven 'MAVEN_HOME' 
      jdk 'JAVA_HOME'
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
