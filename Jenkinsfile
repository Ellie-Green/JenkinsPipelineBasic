pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Stage:'
                echo 'Building the project...'
                sh 'ls -la'
                sh 'pwd'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Stage:'
                echo 'Testing the project...'
                sh 'touch testFile.txt'
                sh 'ls -la'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Stage:'
                echo 'Deploying the project...'
                sh 'mv testFile.txt deployedTestFile.txt'
                sh 'ls -la'
            }
        }
    }
}
