pipeline {

    agent any

    stages {

        stage ('Compile Stage') {

            sh 'mvn -B -DskipTests clean package'
        }
        stage ('Testing Stage') {

            sh 'mvn test'
        }
    }
}