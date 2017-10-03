#!/bin/groovy

pipeline {
    agent any
    stages {
        stage('begin')
            {
                steps {
                echo 'hello world'
                }
            }
        }
    post {
        always {
            echo 'finish'
            }
    }
}
