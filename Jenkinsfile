pipeline {
    agent { label 'my-docker' }
    tools {nodejs "node"}

    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}