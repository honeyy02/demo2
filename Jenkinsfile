pipeline{
  agent any
  environment{
    PYTHON_HOME = ' /home/codespace/.python/current/bin/python'
  }
  stages{
     stage('Check Python Version') {
    steps {
        sh '${PYTHON_HOME} --version'
     }
}
    stage('Build'){
      steps{
        
        sh 'python test.py'
      }
      
    }
   
    
  
  }
}
