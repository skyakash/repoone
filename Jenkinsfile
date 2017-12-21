pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        git(url: 'https://github.com/skyakash/repoone.git', changelog: true, poll: true, branch: 'master')
      }
    }
  }
}