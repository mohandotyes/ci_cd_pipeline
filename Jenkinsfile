pipeline {
 agent any
 tools {
        jdk 'jdk17'
        maven '3.9.9'
    }
   stages{
     stage('checkout') {
       steps {
          checkout scm
       }
     }
     stage('build') {
       steps {
          sh 'mvn clean install'
       }
     }
    
       stage('deploy') {
        steps {
         sh 'mvnw tomcat9:run'
        }
       }
        stage('test') {
          steps {
           echo "testing..."
          }
        }
       }
     }
