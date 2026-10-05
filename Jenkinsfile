pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build is running'
            }
        }

        stage('Test') {
            steps {
                sh 'test -f index.html'
                echo 'Test is running'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy is running'
            }
        }
    }
}
