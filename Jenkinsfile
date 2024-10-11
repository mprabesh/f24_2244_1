pipeline {
    agent any
    stages {
        stage('Info') {
            steps {
                export varName=BUILD_NUMBER
                echo '${'$varName'}'
                echo 'This is Info'
            }
        }
        stage('Build') {
            steps {
                echo 'Build in progress'
                sh 'sleep 5'
            }
        }
         stage('Test') {
            steps {
                echo 'Testing in progress'
                sh 'sleep 5'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deployment in progress'
                sh 'sleep 7'
            }
        }
    }
}
