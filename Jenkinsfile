pipeline{
    agent any

    stages{
        stage('checkout'){
            steps{
                git "https://github.com/Archish1962/exp7.git"
            }
        }

        stage('Build'){
            steps{
                bat 'javac app.java'
            }
        }

        stage('Run'){
            steps{
                bat 'java app.java'
            }
        }

    }
}
