pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat '''
                echo Build Step: Nothing to build for Python
                '''
            }
        }
        stage('Test') {
            steps {
                bat '''
                echo Test Step: Activating venv and running pytest

                RAIE_Lab7\\Scripts\\python.exe -m pytest

                REM Remove the exit 1 below once everything is working
                REM exit 1
                '''
            }
        }
        stage('Deploy') {
            steps {
                bat '''
                echo Deploy Step: Upload artifacts or models here
                '''
            }
        }
    }
}
