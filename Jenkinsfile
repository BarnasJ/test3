pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building2..'
                echo ${MY_NAME}
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
