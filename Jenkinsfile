// Shell commands example
/*
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
*/

// Python build example

pipeline {
    agent any /*{ docker { image 'python:3.10.1-alpine' } }*/
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}

