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
                sh ./HelloWorld.sh
            }
        }
        stage("deploy"){
            steps{
                echo 'Deploying the application'
            }
        }
    
    }
}
