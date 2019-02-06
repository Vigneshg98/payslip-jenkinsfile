pipeline {
    agent any 
    tools {
        maven 'LocalMaven' 
    }
    stages {
        stage('BUILD') {
            steps {
                build 'payslip2.0-build'
            }
        }
        stage('TEST'){
            steps{
                build 'payslip2.0-test'
            }
        }
        stage('DEPLOY'){
            steps{
                build 'payslip2.0-deploy'
            }
        }
    }
}
        
