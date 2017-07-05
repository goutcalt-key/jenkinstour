Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
		sh 'docker info'
            }
        }
    }
    post{
	always {
	    junit 'build/reports/**/*.xml
	}
    }

}
