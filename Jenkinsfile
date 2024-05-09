pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('UnitTest') {
            steps {
                echo 'Unit Testing...'
            }
        }
        stage('SmokeTest') {
            steps {
                echo 'Smoke Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying when tags...'
            }
        }
    }
}