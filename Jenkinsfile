pipeline {
    agent any
    
    tools {
        nodejs "nodejs"
    }

    stages {
        stage("install") {
            steps {
                // sh 'npm install'
                sh 'echo hello world 1'
            }
        }
        stage("build") {
            steps {
                // sh 'npm run build'
                sh 'echo hello world 2'
            }
        }
    } 
    
    post {
        success {
            echo "SUCCESSFUL"
        }
        failure {
            echo "FAILED"
        }
    }
}