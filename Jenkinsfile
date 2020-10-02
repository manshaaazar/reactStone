pipeline{
agent any
  stages{
    stage('npm install'){
      steps{
      nodejs('Node-10.22'){
        sh'npm install'
        sh'npm --version'
        sh'whoami'
        sh'pwd'
      }
      }
    }
    stage('npm build'){
      steps{
      nodejs('Node-10.22'){
      sh'npm run build'
      }
      }
    }
  }
}
