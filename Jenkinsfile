pipeline {
    agent any

    stages {
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
            when { tag "v1." }
            steps {
                echo 'Deploying..'
            }
        }
    }
}