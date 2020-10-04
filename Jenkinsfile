pipeline{
agent any
  stages{
    stage('npm install'){
      steps{
        // // providing tool to perform commands
      nodejs('Node-10.22'){
        sh'npm install'
        sh'npm --version'
      }
      }
    }
   
  }
}
