pipeline {
    agent { label 'slave-1' }
    stages {
        stage('Checkout') {
            steps {
                sh 'echo \'print("hello!")\' > hello.py'
            }
        }
        stage('Build') {
            steps {
                sh 'python3 hello-world.py'
            }
        }
    }
}
