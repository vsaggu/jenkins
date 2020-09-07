pipeline {
    agent { label 'docker-slave-template' }
    stages {
        stage('build') {
            steps {
                sh 'java --version'
                sh 'pwd'
            }
        }
    }
}
