pipeline {
    agent { docker 'maven:4.4.0-83' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
