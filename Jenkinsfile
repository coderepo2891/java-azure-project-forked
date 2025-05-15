pipeline {
    agent any

    stages {
        stage('git clone CHECK') {
            steps {
                git 'https://github.com/coderepo2891/java-azure-project-forked.git'
            }
        }
         stage('mvn package') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
