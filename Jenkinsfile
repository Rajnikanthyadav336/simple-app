pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage('Buld') {
            steps {
                 sh script: 'mvn clean package'
            }
        }

    }

}
