Jenkinsfile (Declarative Pipeline)

pipeline {
    //agent directive: tell Jenkins where and how to execute the Pipeline
    //required for all pipelines
    agent docker{ image 'node:7-alpine'}
    stages {
        stage('build') {
           steps {
                sh 'python --version'
		sh 'echo "hi hi"'
            }
        }
    }
}

