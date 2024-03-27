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
        stage('Stage-3 : Validate') { 
            steps {
                sh 'mvn validate'
            }
        }
        stage('Stage-4 : Compile') { 
            steps {
                sh 'mvn Compile'
            }
        }
        stage('Stage-5 : Test') { 
            steps {
                sh 'mvn Test'
            }
        }
        stage('Stage-6 : Install') { 
            steps {
                sh 'mvn Install'
            }
        }
        stage('Stage-7 : Verify') { 
            steps {
                sh 'mvn Verify'
            }
        }
        stage('Stage-8 : Package') { 
            steps {
                sh 'mvn Package'
            }
        }
  
    }
}
