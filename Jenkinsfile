pipeline {


  agent any

  stages {
    stage("build") {
      steps {
         sh "npm install"
        
      }
  }

  stage("test") {
    
      steps {
        sh "npm run test"
  
      }

    }

  stage("deploy") {
  
    steps {
        echo "In deployment"
    }

  }
  }

}