pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('Clone-Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Ismaililica/DevOpsProject2.git'
            }
        }
    }
}
