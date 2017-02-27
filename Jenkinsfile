pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'Hello World!' 
            }
        }
        stage('Test'){
            steps {
                echo 'hello is to all'
                junit 'reports/**/*.xml' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'make publish'
            }
        }
    }
}
