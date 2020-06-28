pipeline {
    agent none
    stages{
        stage ('Connect to git'){
             steps{
                 checkout scm https://github.com/PPAneesh/jenkin-pipeline
             }
                }

        stage ('Compiling code') {
            steps{
                echo 'Hi Integrate the code'
            }
        }
        stage ('Test the code with inbuilt tools'){
            steps{
                echo 'Test in progress'
            }
        }
    }

post {
    always {
        echo ' I will always say Hello!!!!!'
    }
}
}
