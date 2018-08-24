pipeline {

    agent any
    tools {
        maven 'maven_3_5_4'
      }
    stages {

        stage ('Compile Stage') {

            steps {

                    sh 'maven clean compile'
            }
        }
        stage ('Testing Stage') {

            steps {

                    sh 'mvn test'
            }
        }
    }
}