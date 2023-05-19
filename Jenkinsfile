pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Pipeline stage Start from git repo...'
                echo "Datetime: ${env.BUILD_TIMESTAMP}"
            }
        }
        stage('End') {
            steps {
                echo 'Pipeline stage End from git repo...'
                echo "Datetime: ${env.BUILD_TIMESTAMP}"
            }
        }        
    }
}
