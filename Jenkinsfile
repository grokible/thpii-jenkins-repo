pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('check') {
            steps {
                echo "placeholder"
            }
        }
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}