pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo "Building ${params.name}"
      }
    }
    stage('Test'){
      steps{
        echo "Testing"
      }
    }
    stage('Deploy'){
      steps{
        echo "Deploying"
      }
    }
  }
}
