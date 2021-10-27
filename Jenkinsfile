pipeline {
    agent any
    stages{
        stage ("Git Checkout"){
            steps{
                git 'https://github.com/Tejesh1411/maven-web-application.git'
            }
        }
        stage ("Maven Build"){
            steps{
            sh 'mvn clean install package'
            }
        } 
        stage ("webhook stage"){
            steps{
            echo 'welocme to webhooks'
            }
        }
    }
}
   
