pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        bat '''
          mvn clean install package
          '''
      }
    }
    
  }
  
  
}
