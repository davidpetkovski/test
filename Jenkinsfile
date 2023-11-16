pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                dir('/home/david/test2'){
                    echo 'Pulling branch'
                    git branch: 'main', credentialsId: 'davidgit', url: 'git@github.com:davidpetkovski/test.git'
                }
            }
        }
    }
}
