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
        stage ('tools') {
        maven 'apache-maven-3.0.1' 
    }
    }
        stage('Example') {
            steps {
                sh 'mvn --version'
            }
        }

    }
}


