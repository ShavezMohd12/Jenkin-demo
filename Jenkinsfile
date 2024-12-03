pipeline{
  agent any
  stages{
    stage("Build"){
      steps{
        
      echo "Build"
      }
    }
    stage("test"){
      steps{
        
      echo "test"
      }
    }
  }
  post{
    always{
      echo "all build executed"
    }
    success{
      echo "build success"
    }
    failure
    {
      echo "build failed"
    }
  }
}
