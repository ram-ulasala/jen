pipeline {
    agent { label 'AGENT-1' }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post {
        always {
            echo 'I will ram always say Hello again!'
        }
    }
}