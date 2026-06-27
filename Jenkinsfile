pipeline{
  agent {
    docker { 
            image 'python:3.11-slim' 
        }
  }
  stages{
    stage("Test"){
      steps{
        echo "Hello"
        sh 'python3 hello.py'
    
      }
    }
  }
}
