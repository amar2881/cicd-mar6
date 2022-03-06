pipeline {
    agent any
    stages {
        stage('Example') {
            options {
                timeout(time: 1, unit: 'HOURS') 
            }
            steps {
                echo 'Hello World'
            }
        }
        tools {
        maven 'apache-maven-3.0.1' 
    }
    }
        Example {
            steps {
                sh 'mvn --version'
            }
        }

    }



