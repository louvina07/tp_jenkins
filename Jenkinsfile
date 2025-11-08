
pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo '🧱 Compilation des fichiers Java...'
                sh 'javac HelloWorld.java Merci.java DeRien.java'
            }
        }

        stage('Run HelloWorld') {
            steps {
                echo '🚀 Exécution de HelloWorld.java'
                sh 'java HelloWorld'
            }
        }

        stage('Run Merci') {
            steps {
                echo '🙏 Exécution de Merci.java'
                sh 'java Merci'
            }
        }

        stage('Run DeRien') {
            steps {
                echo '🤝 Exécution de DeRien.java'
                sh 'java DeRien'
            }
        }
    }

    triggers {
        // Exécute automatiquement le pipeline à chaque changement dans le repo
        pollSCM('* * * * *') // toutes les minutes
    }
}
