pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                echo 'Hello World!!!'
                sh 'mvn --version'
                sh 'git --version'
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
