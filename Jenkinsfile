pipeline{
  agent any
  stages{
    stage("Hello"){
      when{
        branch "develop"
      }
      steps{
        echo "This is multi branch pipeline"
      }
    }
  }
}
