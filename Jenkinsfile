// Python build example

pipeline {
    agent any /*{ docker { image 'python:3.10.1-alpine' } }*/
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'python3 ./HelloWorld.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

