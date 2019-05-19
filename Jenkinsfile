pipeline {
    agent any
    tools {nodejs "node"}
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