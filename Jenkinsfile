pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                sh 'git clone https://github.com/Masterhuthiu/test-cpro-cmd.git'
            }
        }
        stage('Build') {
            steps {
                sh 'cmake -S . -B build'
                sh 'cmake --build build'
            }
        }
    }
}
