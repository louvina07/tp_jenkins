pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo '🧑‍💻 Compilation des fichiers Java...'
                // Compile toutes les classes Java du projet
                bat 'javac HelloWorld.java Merci.java DeRien.java'
            }
        }

        stage('Run HelloWorld') {
            steps {
                echo '🚀 Exécution de HelloWorld'
                bat 'java HelloWorld'
            }
        }

        stage('Run Merci') {
            steps {
                echo '🙏 Exécution de Merci'
                bat 'java Merci'
            }
        }

        stage('Run DeRien') {
            steps {
                echo '🙌 Exécution de DeRien'
                bat 'java DeRien'
            }
        }
    }
}
