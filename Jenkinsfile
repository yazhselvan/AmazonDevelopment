
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the new release'
                 build quietPeriod: 5, job: 'amazonDevelop'
            }
        }
        
        
        
 stage('Deploy') {
            steps {
                echo 'Deploying the new release'
                // mail bcc: '', body: 'Deployment completed', cc: 'yazhslvn89@hotmail.com', from: '', replyTo: '', subject: 'Deployment completed', to: 'yazhslvn89@gmail.com'
                
            }
        }
 stage('Test') {
            steps {
                echo 'Testing the new release'
            }
        }
 stage('Release') {
            steps {
                echo 'Final Release!'
            }
        }
    }
}
