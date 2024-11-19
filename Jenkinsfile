pipeline {
    agent any
    environment {
        JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_202'
        PYTHON_HOME = 'C:\\Users\\rehou\\AppData\\Local\\Microsoft\\WindowsApps'
        PATH = "${env.PATH};${JAVA_HOME}\\bin;${PYTHON_HOME}"
    }
    stages {
        stage('Run Script') {
            steps {
                sh 'javac HelloWorld.java && java HelloWorld'
            }
        }
    }
}