pipeline {
    agent any
    stages {
        stage('generate') {
            steps {
                sh 'cmake -G "Unix Makefiles"'
		}
	}	
        stage('build') {
            steps {
                sh 'make'
		}
	}
	}
}	
