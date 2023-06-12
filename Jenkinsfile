pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/BrandonHargitay/personal-site', changelog: true, branch: 'master')
      }
    }

  }
}