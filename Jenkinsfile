pipeline {
    agent {
        docker {
            image 'node:16'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sudo apt update
                sudo apt install nodejs npm

                sh 'npm install' 
            }
        }
    }
}
