pipeline {
    agent any
 stages {
    stage('SCM Checkout') {
            steps {
                echo 'Checkout completed'
                echo 'getting from github'
            }
        }
        stage('BUILD') {
            steps {
                echo 'Build completed'
            }
        }
        stage('Test') {
            steps {
                sh 'date'
            }  
        }
         stage('Deploy') {
            steps {
                echo 'Deploy completed'
            }  
        }
        
    } 
}
