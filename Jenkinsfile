pipeline {
    agent any

    tools {
        nodejs 'node-version-22.6'  // Name as defined in Global Tool Config
    }

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install --no-audit'
            }
        }
    }
}
