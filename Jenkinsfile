pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                def scmVars = checkout scm
            }
        }
        stage('Test') {
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
