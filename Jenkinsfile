pipeline{

    agent any

    stages{
        stage('Git checkout'){

            steps{
                git branch:'master', url:'https://github.com/youngmind01/E2E-java-CICD-pipeline.git'
            }
        }
        stage('Unit test'){
            steps{
                sh 'mvn test'
            }
        }
    }
}