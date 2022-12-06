pipeline {
    agent any 
    stages {
        stage('Demo stage 1') {
            steps {
                sh "ls"
                sh "pwd"
                // sh "mkdir pipeline_demo"
                sh "cd pipeline_demo"
                sh "ls"
            }
        }
        stage('Build Stage') {
            steps {
                sh "chmod +x ./buildScript.sh"
                sh "./buildScript.sh"
            }
        }
    }
}