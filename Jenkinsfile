pipeline {
    agent any
  stages {
    stage("create zip file"){
        steps {
            script {
             zip middlewarescript-${BUILD_NUMBER}.zip * -x Jenkinsfile README.md    
            }
        }
    }
    
    }
  }
}