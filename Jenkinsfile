pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('Test') {
            steps {
                echo 'Hello World!!!'
                sh 'git --version'
                sh 'mvn --version'
            }
        }
    }
}
