pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {

                sh 'node --version'
                sh 'cat /etc/os-release'
                sh 'npm install'
                sh 'npm build'
            }
        }
    }
}
