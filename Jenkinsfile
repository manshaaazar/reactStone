pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/manshaaazar/react-dep.git', branch: 'master')
      }
    }

    stage('install dep') {
      steps {
        sh 'npm install '
      }
    }

    stage('build') {
      steps {
        sh 'npm run build'
      }
    }

    stage('pwd') {
      steps {
        sh 'pwd'
      }
    }

  }
}