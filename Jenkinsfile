pipeline {
    agent {
	    label 's1'
    }

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/varalakshmikonjeti/26Jenkins.git'
                sh "python3 main.py"
		        sh "java Demo.java"
            }
        }
    }
}
