pipeline {
    agent any

    stages {
        stage('Check Node and NPM Version') {
            steps {
                script {
                    echo 'Checking Node.js and npm versions...'
                }
                sh '''
                    node -v
                    npm -v
                '''
            }
        }
    }
}
