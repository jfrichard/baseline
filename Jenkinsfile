pipeline {
    agent any
    
    stages {
        stage('Build') { 
            steps { 
                echo 'Hello World'
                build 'Helloworld'
            }
        }
        stage('Build2') {
            steps { 
                echo 'Hello World2'
                build 'Helloworld2'
            }
        }
    }
}