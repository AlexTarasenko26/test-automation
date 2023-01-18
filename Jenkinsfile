Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'php:7.4.0-fpm-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}