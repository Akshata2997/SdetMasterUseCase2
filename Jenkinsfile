pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                dir("Akshata-Shinde-RestfulAndSoapWS2") {
		bat "mvn clean"
	}
            }
        }
        stage('Compile') {
            steps {
	dir("Akshata-Shinde-RestfulAndSoapWS2") {
		bat "mvn compile"
	}
            }
        }
        stage('Test') {
            steps {
	dir("Akshata-Shinde-RestfulAndSoapWS2") {
		bat "mvn test"
	}
            }
        }
        stage('Result') {
            steps {
                echo "Result"
            }
        }
    }
}
