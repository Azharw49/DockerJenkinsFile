pipeline {
    agent {
         docker {
                    image 'jenkins/slave'
                }
            }  
    stages {
        stage('Compile') {
            steps {
                sh 'java -v'
                sh 'pwd'
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
