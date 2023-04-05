pipeline {
    agent { label 'slave-1' }
    stages {
        stage('Checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '89df1d98-c29d-425d-bc8e-539ea25ef40b', url: 'https://github.com/fmerchant31/Hello-World-Jenkins.git']])
            }
        }
        stage('Build') {
            steps {
                sh 'python3 hello-world.py'
            }
        }
    }
}
