pipeline {
    agent any
    stages {
      stages('Deps') {
        steps {
                sh 'make deps'
            }
      }
        stage('Test') {
            steps {
                    sh 'make test'
              	}
        }
    }
}
