pipeline {
    agent any
         tools {
            nodejs "NodeFromNVM"
    }
    stages {
        stage('VM Node version') {
            steps {
                sh '''
                   node -v
                    npm -v
                '''
            }
        }
    }
}