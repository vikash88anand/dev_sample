pipeline {
    agent any
    stages {
        stage('Welcome Step') {
            steps { 
                echo 'Welcome to Test'
                bat """
                cd Code_Base
                run.bat
                """
            }
        }
    }
}
