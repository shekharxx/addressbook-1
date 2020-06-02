pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                sh '/usr/local/src/apache-maven/bin/mvn -B clean verify'
            }
        }
    }
}
