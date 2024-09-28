pipeline {
    agent any
    tools { 
        maven 'maven' 
        jdk 'jdk' 
    }
    stages {
        stage ('Initialize') {
            steps {
                   sh 'mvn -B -DskipTests clean package' 
            }
        }

        stage ('Build') {
            steps {
                echo 'This is a minimal pipeline.'
            }
        }
    }
}