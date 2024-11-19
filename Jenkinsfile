pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                sh 'javac HelloWorld.java && java HelloWorld'
            }
        }
    }
}