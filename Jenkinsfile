pipeline {
    agent { docker { image 'node:8.3' } }
    stages {
        stage('install') {
            steps {
                sh 'npm install'
            }
        }

        stage('build') {
            steps {
                sh 'ng build --prod'
            }
        }
    }
}