pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'csea',
                    url: 'https://github.com/spidey-4web/Deoops.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac New.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java New'
            }
        }
    }
}
