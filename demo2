pipeline{
  stages{
    stage("Build"){
      echo "Build"
    }
    stage("test"){
      echo "test"
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
