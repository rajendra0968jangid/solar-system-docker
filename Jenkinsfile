pipeline {
    agent any

    tools {
        nodejs 'node-version-22.6'  // Name as defined in Global Tool Config
    }
    environment {
        MONGO_USERNAME = 'rajendra0968jangid'
        MONGO_PASSWORD = 'Hu9RLEvt926c6dYj'
        NODE_ENV = 'development'
        MONGO_URI = "mongodb+srv://${MONGO_USERNAME}:${MONGO_PASSWORD}@cluster0.wyu84.mongodb.net/solar-system"
    }
    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install --no-audit'
            }
        }
        stage('Run the project') {
            steps {
                sh 'npm run start'
            }
        }
    }
}

