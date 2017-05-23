Jenkinsfile (Declarative Pipeline)

pipeline {
    //agent directive: tell Jenkins where and how to execute the Pipeline
    agent any
    stages {
        stage('build') {
           steps {
                sh 'python --version'
		sh 'echo "hi hi"'
            }
        }
    }
}

