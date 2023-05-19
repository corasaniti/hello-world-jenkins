pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Pipeline stage Start from git repo...'
               script {
                    def timestamp = currentTimestamp()
                    def formattedTimestamp = new SimpleDateFormat("yyyy-MM-dd'T'HH:mm:ssX").format(timestamp)
                    echo "Timestamp: ${formattedTimestamp}"
                }
            }
        }
        stage('End') {
            steps {
                echo 'Pipeline stage End from git repo...'
                script {
                    def timestamp = currentTimestamp()
                    def formattedTimestamp = new SimpleDateFormat("yyyy-MM-dd'T'HH:mm:ssX").format(timestamp)
                    echo "Timestamp: ${formattedTimestamp}"
                }
            }
        }        
    }
}
