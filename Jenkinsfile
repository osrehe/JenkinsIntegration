pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Bye') {
            steps {
                echo 'Good bye'
            }
        }
        stage('sh') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
