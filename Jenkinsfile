pipeline {
    agent any 
    stages {
        stage('Stage-1 : Clean') { 
            steps {
                sh 'mvn clean'
            }
        }
        stage('Stage-2 : Validate') { 
            steps {
                sh 'mvn validate'
            }
        }
        stage('Stage-2 : Validate') { 
            steps {
                sh 'mvn validate'
            }
        }
        stage('Stage-2 : Compile') { 
            steps {
                sh 'mvn Compile'
            }
        }
        stage('Stage-2 : Test') { 
            steps {
                sh 'mvn Test'
            }
        }
        stage('Stage-2 : Install') { 
            steps {
                sh 'mvn Install'
            }
        }
        stage('Stage-2 : Verify') { 
            steps {
                sh 'mvn Verify'
            }
        }
        stage('Stage-2 : Package') { 
            steps {
                sh 'mvn Package'
            }
        }
  
    }
}
