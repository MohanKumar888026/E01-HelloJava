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
        stage('Stage-4 : Test') { 
            steps {
                sh 'mvn Test'
            }
        }
        stage('Stage-5 : Install') { 
            steps {
                sh 'mvn Install'
            }
        }
        stage('Stage-6 : Verify') { 
            steps {
                sh 'mvn Verify'
            }
        }
        stage('Stage-7 : Package') { 
            steps {
                sh 'mvn Package'
            }
        }
  
    }
}
