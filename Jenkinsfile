pipeline {
    agent any

    stages {
        stage('Switch Directory and List') {
            steps {
                script {
                    // Change to your desired directory
                    dir('myfolder') {
                        sh 'pwd'
                        sh 'ls -l'
                    }
                }
            }
        }
    }
}
