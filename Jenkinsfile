pipeline {
    agent any

    environment {
        MY_PASSWORD = credentials('MY_PASSWORD')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo $MY_PASSWORD
                echo $MY_PASSWORD_USER
                echo $MY_PASSWORD_PASS
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