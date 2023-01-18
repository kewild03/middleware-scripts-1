pipeline {
    agent any
  stages {
    stage("create zip file"){
        steps {
            sh 'zip middlewarescript-${BUILD_NUMBER}.zip * -x Jenkinsfile README.md'
            }
        }
    }
    
    }
  }
}