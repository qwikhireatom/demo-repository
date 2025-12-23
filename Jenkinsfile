pipeline {
  agent any

  triggers {
    githubPush()
  }

  stages {
    stage('Checkout') {
      steps {
        git branch: 'main',
            url: 'https://github.com/qwikhireatom/demo-repository.git'
      }
    }

    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }
  }
}
