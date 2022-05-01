pipeline {
    tools {
        'org.jenkinsci.plugins.docker.commons.tools.DockerTool' 'docker'
    }
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}