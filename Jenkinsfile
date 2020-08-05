pipeline {
    agent { node {label 'master'}}
    stages {
        stage('Build') {
            when {
                branch 'develop'
            }
            steps {
                sh 'composer install'
            }
        }
    }
}