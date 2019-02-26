pipeline {
    agent any
    stages{
        
        stage('Git Clone or Pull'){
            
            steps {
                git 'https://github.com/asquarezone/spring-petclinic.git'
            }
        }
        
        stage('Maven Build'){
            steps{
                sh 'mvn clean install'
                } 
             }
           }
       }
        
