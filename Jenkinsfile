pipeline {
    agent any 
    stages {
        stage('clone') { 
            steps {
                sh "rm -rf *"
                sh "git clone https://github.com/sofiane-lablack/tp_pipepline_jenkins"
                // 
            }
        }
        stage('build') { 
            steps {
                sh "cd tp_pipepline_jenkins/ && javac Main.java"
                // 
            }
        }
        stage('run') { 
            steps {
                sh "cd tp_pipepline_jenkins/ && java Main"
                // 
            }
        }
    }
}
