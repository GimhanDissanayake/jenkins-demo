pipeline {
    agent any

    stages {
        stage('source') {
            steps {
                echo 'source downloaded'
            }
        }
        stage('build') {
            steps {
                echo 'building...'
            }
        }
        stage('test') {
            steps {
                echo 'testing...'
                sh 'cat readme.txt'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying...'
            }
        }
    }
}
