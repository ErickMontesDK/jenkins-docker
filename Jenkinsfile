pipeline {

    agent any
    
    stages{
        stage(""){
            steps{
                echo 'Building the application'
            }
        }
        stage("test"){
            steps{
                sh 'chmod +x helloWorld.sh'
                sh './helloWorld.sh'
            }
        }
        stage("deploy"){
            steps{
                echo 'Deploying the application'
            }
        }
    
    }
}
