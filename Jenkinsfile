pipeline {
    agent { 
        node('test-worker-node')
}

    stages {
        stage('Build') {
            steps {
                script {
                    // Execute Linux commands
                    sh 'echo "Running Linux commands"'
                  }
            }
        }
        
        stage('Test') {
            steps {
                script {
                    // Execute more Linux commands
                    sh 'echo "Running tests"'
                    
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    // Execute deployment commands
                    sh 'echo "Deploying application"'
                    
                }
            }
        }
    }
}
