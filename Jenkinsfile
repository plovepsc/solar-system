pipeline {
    agent any

    stages {
        stage('Check Node & NPM Version') {
            steps {
                echo 'Checking Node.js and NPM versions...'
                sh '''
                    echo "Node.js Version:"
                    node -v

                    echo "NPM Version:"
                    npm -v
                '''
            }
        }
    }
}

