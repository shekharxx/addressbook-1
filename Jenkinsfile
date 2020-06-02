pipeline {
    agent any
    stages {
        stage('Compiling') {
            steps {
                sh '/usr/local/src/apache-maven/bin/mvn compile'
            }
        }
        stage('Testing') {
            steps {
                sh '/usr/local/src/apache-maven/bin/mvn test'
            }
        }
        stage('Packagin') {
            steps {
                sh '/usr/local/src/apache-maven/bin/mvn package'
                
            }
        }
    }
}
