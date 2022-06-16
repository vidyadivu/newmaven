pipeline{
    agent any

    stages{
        // stage('Cloning Repository'){

        // }

        stage('Building the code'){

            sh 'mvn clean compile'

        }

        stage('Packaging the code'){

            sh 'mvn package'

        }

        stage('Testing the code'){

            sh 'mvn test'

        }


    }
}