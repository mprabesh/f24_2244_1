pipeline {
    agent any
    stages {
        stage('Info') {
            steps {
                echo "Job: ${JOB_NAME} is building on branch ${BRANCH_NAME} and build-id is ${BUILD_ID}"
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
