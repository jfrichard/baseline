pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
		sh '/usr/bin/java -version'
                sh 'echo "Hello World"'
            }
        }
    }
}
