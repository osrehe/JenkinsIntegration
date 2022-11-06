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
        stage('Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
    }
}
