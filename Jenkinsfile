pipeline {
    agent any
    
    stages {
        stage('pull code') {
            steps {
               git branch: 'main', url: 'https://github.com/jenkinsci/jenkinsfile-runner.git' 
            }
        }
        
        stage('Build') {
            steps {
               echo 'code build successfully'
            }
        }
        
        stage('store') {
            steps {
                echo 'stored code successfully'
            }
       
        }
    }
}
