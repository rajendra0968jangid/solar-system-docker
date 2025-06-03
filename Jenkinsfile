pipeline {
    agent any

    environment {
        MONGO_USERNAME = 'rajendra0968jangid'
        MONGO_PASSWORD = 'Hu9RLEvt926c6dYj'
        NODE_ENV = 'development'
        MONGO_URI = "mongodb+srv://${MONGO_USERNAME}:${MONGO_PASSWORD}@cluster0.wyu84.mongodb.net/solar-system"
    }

    stages {
        stage('Print Mongo Environment') {
            steps {
                sh '''
                    echo "Mongo URI: $MONGO_URI"
                    echo "Environment: $NODE_ENV"
                '''
            }
        }
    }
}
