pipeline {
    agent any
   tools {
        maven 'maven_3.1.0'
        jdk 'JDK_1.8'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo "The maven version used is"
                bat 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
