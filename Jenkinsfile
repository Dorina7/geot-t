pipeline{
    agent any 
    stages {
        stage('maven clean'){
            steps{
                sh 'mvn clean'
            }
        }
        stage('maven install'){
            steps{
                sh 'mvn isntall'
            }
        }
        stage('maven package'){
            steps{
                sh 'mvn package'
            }
        }
    }

}