pipeline{
    agent any

    stages{
        // stage('Cloning Repository'){

        // }
        stage('Building the code'){
          steps{
            sh 'mvn clean compile'

          }
        }

        stage('Packaging the code'){
            steps{

            sh 'mvn package'
            }

        }

        stage('Testing the code'){
            steps{
             sh 'mvn test'

          }
        }
    }
}