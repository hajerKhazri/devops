pipeline {
    agent any
    
    stages {
        stage('🚀 Branche Fares') {
            steps {
                echo 'Pipeline de la branche Fares!'
            }
        }
        
        stage('📁 Analyse') {
            steps {
                sh 'ls -la'
                echo 'Fichiers de la branche fares'
            }
        }
        
        stage('🔧 Outils') {
            steps {
                sh 'java -version'
                sh 'mvn --version'
            }
        }
        
        stage('🎉 Succès') {
            steps {
                echo 'BRAVO! Votre branche fares fonctionne!'
            }
        }
    }
}
