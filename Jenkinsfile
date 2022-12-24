pipeline {
    agent any

    stages {
        stage('Build') {
            steps {                
                sh "whoami"
               
                // Install nginx.
                sh "apt-get update"
                sh "apt-get install nginx"
            }
       }
    }
}
