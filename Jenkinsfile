pipeline {
    agent any 
    stages {
        stage('clone') { 
            steps {
                sh "rm -rf *"
                sh "git clone https://github.com/sofiane-lablack/tp_pipepline_jenkins.git
                // 
            }
        }
        stage('build') { 
            steps {
                sh "cd jenkins-helloworld/ && javac Main.java"
                // 
            }
        }
        stage('run') { 
            steps {
                sh "cd jenkins-helloworld/ && java Main"
                // 
            }
        }
    }
}
