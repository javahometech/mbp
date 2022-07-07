pipeline{
  agent any
  stages{
    stage("Maven Build"){
      when{
        branch "develop"
      }
      steps{
        echo "maven clean package......"
      }
    }
    stage("Sonar Analysis"){
      when{
        branch "develop"
      }
      steps{
        echo "sonar analysis......"
      }
    }
    stage("Dev Deploy"){
      when{
        branch "develop"
      }
      steps{
        echo "deploying to dev......"
      }
    }
    stage("Prod Deploy"){
      when{
        branch "main"
      }
      steps{
        echo "deploying to prod......"
      }
    }
  }
}
