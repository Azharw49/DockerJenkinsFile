pipeline {
    agent 
    {
        label 'windows'
    }   
    stages {
        stage('Compile') {
            steps {
                bat 'java -version'
                echo "Compile Done"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy Done"
            }
        }
        stage('Test') {
            steps {
                echo "Test Done"
            }
        }
        stage('Release') {
            steps {
                echo "Release Done"
            }
        }
    }
}
