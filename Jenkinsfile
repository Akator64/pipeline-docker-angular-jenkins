pipeline {
    agent { label 'nodejs8' } 
    stages {
        stage('install') {
            sh 'npm install'
        }

        stage('build') {
            sh 'ng build --prod'
        }
    }
}