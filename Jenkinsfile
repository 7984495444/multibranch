pipeline {
  agent any
  stages{
    stage('test') {
      steps{
        echo "successfully"
      }
    }
    stage('clone') {
      steps{
        git branch: 'dev', url: 'https://github.com/7984495444/multibranch.git'
      }
    }
  }
}
