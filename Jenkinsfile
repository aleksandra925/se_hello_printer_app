pipeline {
    agent any
    stages {
        stage('Deps') {
            steps {
              sh 'make deps'
            }
          }
        stages('Linter') {
          steps {
            sh "make linter'
          }
        }
        stages('Test') {
          steps {
            sh 'make test'
          }
        }
    }
}
