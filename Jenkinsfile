pipeline {
  agent any
  tools {
    maven 'Maven_3.8.6'
  }
  stages{
    stage("build") {
      steps{
        echo 'building the application...'
        
      }
    }
    
    stage("test") {
      steps{
        echo 'application built...'
        echo 'testing the application...'
        sh 'mvn -v'
      }
    }
    
    stage("deploy") {
      steps{
        echo 'deploying the application...'
      }
    }
  }
}

node{
    // groovy script
}
