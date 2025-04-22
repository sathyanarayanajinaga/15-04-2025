pipeline {
    agent any
    stages {
       stage("Clone the code"){
          steps{
              git branch: 'master', url: 'https://github.com/sathyanarayanajinaga/15-04-2025.git'
          }
       }    
       stage("Test"){
          steps{
              sh "mvn test"
          }
       }    
       stage("Compile"){
          steps{
              sh "mvn compile"
          }
       }    
       stage("Package"){
          steps{
              sh "mvn package"
          }
       }
    }
}
