pipeline {
    agent { label 'slave-1' }
    stages {
        stage('Hello') {
            steps {
                echo "print(Hello World! jenkins)" > hello-world.py
            }
        }
    }
}
