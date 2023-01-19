pipeline {
    agent any

    stages{
        stage("Compress file"){
            steps{
               
           sh 'zip middlewareScript-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md '  
            
            }
        }
        
    }
}
