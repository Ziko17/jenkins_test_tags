pipeline {
    agent any

    stages {
        stage('Build') {
            when { tag "v*" }
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            when { tag "v*" }
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            when {
                buildingTag()
            }
            steps {
                echo 'Deploying when tags..'
            }
        }
    }
}