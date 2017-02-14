pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
		sh 'java -version'
                sh 'echo "Hello World"'
            }
        }
    }
}
