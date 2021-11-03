pipeline {

    agent any
    tools {
        maven 'mvn' 
        jdk 'jdk'
    }
    stages {
        stage('Compile stage') {
            steps {
                sh 'mvn clean' 
                sh 'mvn install'
        }
    }

         stage('testing stage') {
             steps {
                sh 'mvn test'
        }
    }


  }

}
