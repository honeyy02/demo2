pipeline{
  agent{
     docker{
    image 'python:3.8'
  }
  } 
 
  stages{
//      stage('Check Python Version') {
//     steps {
//         sh '${PYTHON_HOME} --version'
//      }
// }
    stage('Build'){
      steps{
        
        sh 'python3 test.py'
      }
      
    }
  }
  post{
    always{
      echo 'Pipeline Completed'
    }
  }
}
