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
        stage('Stage-4 : Install') { 
            steps {
                sh 'mvn Install'
            }
        }
        stage('Stage-5 : Verify') { 
            steps {
                sh 'mvn Verify'
            }
        }
        stage('Stage-6 : Package') { 
            steps {
                sh 'mvn Package'
            }
        }
  
    }
}
