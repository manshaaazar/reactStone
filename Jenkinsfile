pipeline {
  agent any
  stages {
   
    }

    stage('npm install') {
      steps {
        nodejs('Node-10.22'){
          
        sh 'npm install '
        sh 'npm --version'
        sh 'npm build'
        }
      }
    }
    stage('pwd') {
      steps {
        sh 'pwd'
      }
    }

  }
}
