pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Sappireddyraviteja/JobRepo'
                }
            }
            
        stage('Build') {
            steps {
                sh 'cd /home/administrator/Aswathy'
                sh 'g++ SampleProgram.cpp'
                sh './a.out'
                }
            }
          

            post {
                success {
                    echo 'Code cloned successfully'
                }
            }
        }
    }
}
