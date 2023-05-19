pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Pipeline stage Start from git repo...'
               script {
                    def timestamp = currentTimestamp()
                    echo "Timestamp: ${timestamp}"
                }
            }
        }
        stage('End') {
            steps {
                echo 'Pipeline stage End from git repo...'
                script {
                    def timestamp = currentTimestamp()
                    echo "Timestamp: ${timestamp}"
                }
            }
        }        
    }
}
