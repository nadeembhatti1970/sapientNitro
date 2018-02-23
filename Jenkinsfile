pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build 1'){
          agent docker { image 'httpd' }
    
        }
        stage('Build 2'){
          agent docker{ image 'httpd' }
        }
      }      
    }
   
            
  }
}
