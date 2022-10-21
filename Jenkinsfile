pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        success {
            emailext body: 'This is demo email..', subject: 'Jenkins Email Notification', to: 'mukesh.kondaveeti777@gmail.com'
        }
    }
}
