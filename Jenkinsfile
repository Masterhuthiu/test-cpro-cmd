pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/yourusername/MyCppProject.git'
            }
        }
        stage('Build') {
            steps {
                bat 'cl main.cpp /EHsc'
            }
        }
        stage('Run') {
            steps {
                bat 'main'
            }
        }
    }
}
