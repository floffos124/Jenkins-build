pipeline {
    agent { label 'bletchley' } // Gebruik het label van de Node

    stages {
        stage('Checkout and Build') {
            steps {
                // Pas aan naar jouw repo details en credential ID
                git credentialsId: '', branch: 'main', url: 'url: 'https://github.com/floffos124/Jenkins-build.git''

                // Vervang dit met de feitelijke build-commando's voor C# of je gekozen taal
                sh 'ls -l' 
                sh 'echo "Simulatie van een buildstap..."'
                // Voeg hier de build-commando's toe die de eerste keer falen
                sh 'dotnet build'
            }
        }
    }
}


