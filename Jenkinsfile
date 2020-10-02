pipeline{
agent any
  envoitnment{}
  tools{}
  stages{
    stage('npm install'){
      nodejs('Node-10.22'){
        sh'npm install'
        sh'npm --version'
        sh'whoami'
        sh'pwd'
      }
    }
    stage('npm build'){
      nodejs('Node-10.22'){
      sh'npm build'
      }
    }
  }
}
