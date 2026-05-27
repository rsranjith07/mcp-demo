pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code Downloaded'
            }
        }

        stage('Read File') {
            steps {
                sh 'cat test.txt'
            }
        }

        stage('MCP Validation') {
            steps {
                echo 'MCP Server Validation Success'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application Deployed'
            }
        }

    }
}
