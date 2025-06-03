pipeline {
    agent any

    tools {
        nodejs 'node-version-22.6'  // Name as defined in Global Tool Config
    }

    stages {
        stage('Check Node and NPM Version') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
    }
}
