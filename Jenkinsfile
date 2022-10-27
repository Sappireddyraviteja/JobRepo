pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/Sappireddyraviteja/JobRepo'
            }

            post {
                success {
                    echo 'Code cloned successfully'
                }
            }
        }
    }
