pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Josepf's page"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}
