pipeline {
    agent any

    stages {
        when { tag "v*" }
        stage('Build') {
            steps {
                echo 'Building..'
                echo 'Building 2..'
                echo 'Building 3..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying..'
            }
        }
    }
}