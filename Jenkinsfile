pipeline {


  agent any

  stages {
    stage('build') {
    sh 'npm install'
    sh 'npm start'
  }

  stage('test') {
    sh 'npm run test'
  }

  stage('deploy') {
    echo 'In deployment'
  }
  }

}