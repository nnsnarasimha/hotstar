pipeline {
    agent any

    stages {
        stage('Clone the code') {
            steps {
                // Get some code from a GitHub repository
                git credentialsId: 'git', url: 'https://github.com/nnsnarasimha/hotstar.git'

            }
        }
    }
}