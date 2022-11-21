pipeline {
  agent any
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
        withMaven() {
          sh 'mvn -v'
        }
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
