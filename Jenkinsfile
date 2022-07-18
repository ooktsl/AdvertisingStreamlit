pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('build') {
            steps {
                echo 'Building..'
                sh 'node --version'
            }
        }
        stage('Test') { 
            steps {
                echo 'Test..'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploy..'
            }
        }
    }
}
