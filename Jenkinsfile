@Library('shared-library-task') _

pipeline {
    agent any
    stages {
        stage('Send Greeting') {
            steps {
                // Call the shared library function
                greet("rahma")
            }
        }
    }
}
