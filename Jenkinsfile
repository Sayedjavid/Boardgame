pipeline {    
    agent any 
<<<<<<< HEAD
=======
        
>>>>>>> 1e32735af1a63840f90fd0501b31ec2c5a4bdd24
    tools {
        jdk 'jdk17'
        maven 'maven3'
    }

    stages {   
        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
        
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
