pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Masterhuthiu/test-cpro-cmd'
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
