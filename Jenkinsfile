pipeline {
    agent any

         tools {
            nodejs "NodeFromNVM"
    }

    stages {
        stage('Installing Dependencies') {
            steps {
                sh 'npm install --no-audit'
            }
        }
    }
}