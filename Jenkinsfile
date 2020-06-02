pipeline {
	agent any
	stages {
		stage ('compile') {
			sh 'mvn compile'
		}
		stage ('test') {
			sh 'mvn test'
		}
		stage ('deploy) {
			sh 'mvn deploy'
		}
		stage ('Completion') {
			echo 'Completed'
		}
	}
}
