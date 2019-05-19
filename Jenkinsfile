pipeline {
    agent { label 'nodejs8' } 
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