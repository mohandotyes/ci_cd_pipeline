pipeline {
 agent any
   stages{
     stage('checkout') {
       steps {
          checkout scm
       }
     }
     stage('build') {
       steps {
          echo "maven"
       }
     }
    
       stage('deploy') {
        steps {
         echo "deploying...."
        }
       }
        stage('test') {
          steps {
           echo "testing..."
          }
        }
       }
     }
