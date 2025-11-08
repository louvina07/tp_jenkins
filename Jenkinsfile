pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo '🧑‍💻 Compilation des fichiers Java...'
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run HelloWorld') {
            steps {
                bat 'java HelloWorld'
            }
        }

        stage('Run Merci') {
            steps {
                bat 'java Merci'
            }
        }

        stage('Run DeRien') {
            steps {
                bat 'java DeRien'
            }
        }
    }
}
