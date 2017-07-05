pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
		sh 'ls'
            }
        }
    }
    post {
	always {
		echo 'TEEESTING'
	}
    }	

}
