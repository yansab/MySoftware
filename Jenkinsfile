properties([pipelineTriggers([pollSCM('30 * * * *')])])
pipeline {
    agent any

    stages {
        stage('New Button') {
            steps {
                bat 'C:\\Users\\yaniv\\AppData\\Local\\Programs\\Python\\Python39\\python.exe button.py'
            }
        }
        stage('New Screen') {
            steps {
                bat 'C:\\Users\\yaniv\\AppData\\Local\\Programs\\Python\\Python39\\python.exe screen.py'
            }
        }
    }
}
