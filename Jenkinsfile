pipeline {
    agent any

    stages {
        stage('VM Node version') {
            steps {
                sh '''
                    echo "VM Node version: $(node -v)"
                    echo "VM NPM version: $(npm -v)"
                '''
            }
        }
    }
}