pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                echo 'Hello World!!!'
                sh 'svn --version'
            }
        }
    }
}
