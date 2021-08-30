pipeline {
    agent any
    stages {
        stage('Example Build') {
             withMaven {
                sh "mvn clean verify"
             } 
            steps {
                echo 'Hello, Maven'
               
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
