pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'git clone https://github.com/IrfanNazeeer/IndexFile.git'
             }
        }
        stage('test') {
            steps {
                echo 'tesing stage'
            }
          }
        stage('deploy') {
            steps {
                echo 'deploying stage'
                echo 'hi'
            }
        }
    }
}
