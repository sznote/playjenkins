pipeline {
    agent {
        docker { 
            image 'node:14-alpine'
            label 'agent1'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
