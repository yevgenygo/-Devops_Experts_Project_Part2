pipeline {
    agent any

    stages {
        stage('checkout code') {
            steps {
                echo 'Building..'
		git 'https://github.com/yevgenygo/jenkinsfile'
            }
        }
        stage('run restAPI') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}