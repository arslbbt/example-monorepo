pipeline {
    agent { label 'my-docker' }
    tools {nodejs "node"}

    stages {
        stage('build') {
            steps {
                sh 'node --version'
                sh 'npm install -g nx'
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}