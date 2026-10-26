pipeline {
    agent any
    stages{
        stage("Bulid_stage"){
            steps{
                echo "Building project5 ...."
            }
        }
        stage("Test_stage"){
            steps{
                echo "Testing Project...."
            }
        }
        stage("Deploy_stage"){
            steps{
                echo "Deploying Project...."
            }
        }
    }
    post{
        failure{
            echo "Thank You"
        }
    }
}
