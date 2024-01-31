properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Execute Python Script') {
            steps {
                // Run Python script using sh step
                sh 'python3 1.py'
            }
        }
    }
}

