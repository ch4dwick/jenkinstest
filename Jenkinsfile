pipeline {
    agent { docker 'maven:4.4.0-83-generic' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
