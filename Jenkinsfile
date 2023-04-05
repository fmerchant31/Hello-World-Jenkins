pipeline {
    agent { label 'slave-1' }
    stages {
        stage('Hello') {
            steps {
                sh 'echo \'print("hello!")\' > hello.py'
                sh 'python3 hello.py'
            }
        }
    }
}
