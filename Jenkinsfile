pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changeRequest()
            }
            steps {
                echo "Hello world change request"
            }
        }
    }
}