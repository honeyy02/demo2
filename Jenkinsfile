pipeline{
  agent any
  environment{
    PYTHON_HOME = ' /home/codespace/.python/current/bin/python'
  }
  stages{
    stage('Build'){
      steps{
        
        sh 'python test.py'
      }
      
    }
    stage('Check Python Version') {
    steps {
        sh '${PYTHON_HOME} --version'
    }
}
    
  
  }
}
