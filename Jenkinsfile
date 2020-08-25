pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
	stage('Email') {
            steps {
                mail bcc: '', body: 'Hello', cc: '', from: '', replyTo: '', subject: 'Hello', to: 'devendradhoot@gmail.com'
            }
        }
    }
}
