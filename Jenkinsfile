pipeline {
    agent { label 'slave-1' }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World!(Jenkins)' > hello-world.py
            }
        }
    }
}
