pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Josepf's page"
                sh 'echo using shell within Jenkinsfile'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
                echo 'not using shell in the Jenkinsfile........'
            }
        }
    }
}
