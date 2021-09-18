pipeline {
    agent any
    //tools {
        //maven 'Maven 3.8.2'
    //}
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
                sh 'mvn -v'
            }
        }
        stage('Example Test') {
            
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
    }
}
