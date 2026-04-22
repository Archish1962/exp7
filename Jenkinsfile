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
                sh javac app.java
            }
        }

        stage('Run'){
            steps{
                sh java app.java
            }
        }

    }
}