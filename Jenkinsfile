pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World build is in progress"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
         stage('deploy') {
            steps {
                sh 'echo "Hello World deployment is in progress"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
         stage('smoke') {
            steps {
                sh 'echo "Hello World smoke test is inprogress"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
         stage('regression') {
            steps {
                sh 'echo "Hello World smoke test is regression"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
