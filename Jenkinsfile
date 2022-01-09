def name;
pipeline {
    agent any
    stages {
        stage('Build Stage') {
            steps {
                script{
                bat "gradlew build --scan"
                    }
            }
        }
                
    }
}
