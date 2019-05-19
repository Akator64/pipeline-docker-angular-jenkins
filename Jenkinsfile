pipeline {
    agent any
    tools {nodejs "node"}
    stages {
        stage('install') {
            steps {
                sh 'npm install --loglevel verbose'
            }
        }

        stage('build') {
            steps {
                sh 'npm run ng build --prod'
            }
        }
    }
}