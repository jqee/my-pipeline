pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
				sh 'sudo -i'
                sh 'mvn --version'
            }
        }
    }
}