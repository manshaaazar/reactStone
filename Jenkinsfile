pipeline {
  agent any
  stages {
    stage('Pwd') {
      parallel {
        stage('Pwd') {
          steps {
            sh 'pwd'
          }
        }

        stage('Clone Repo') {
          steps {
            git(url: 'https://github.com/manshaaazar/react-dep.git', branch: 'master')
          }
        }

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

    stage('deploy') {
      steps {
        sh 'server -s build'
      }
    }

  }
}