pipeline {
    agent { 
        node('test-worker-node')
}

    stages {
        stage('my-path') {
            steps {
                script {
                    // Execute Linux commands
                    sh 'echo "Current Location"'
                    sh 'pwd'
                    
                  }
            }
        }
        
        stage('Creating-Directory') {
            steps {
                script {
                    // Execute more Linux commands
                    sh 'echo "Creating Directory with Jenkinsfile"'
                    sh 'mkdir testdirect'
                }
            }
        }

        stage('Verification') {
            steps {
                script {
                    // Execute Verification commands
                    sh 'echo "Verifying Directory"'
                    sh 'ls -la'
                    
                }
            }
        }
    }
}
