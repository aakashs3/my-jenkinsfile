pipeline {
    agent { label "agent" }
    stages{
        stage("code-pull"){
            steps{
                git branch: 'main', url: 'https://github.com/aakashs3/EasyCRUD.git'
            }
        }
        stage("build"){
            steps{
                echo "code build successfull"
            }
        }
        stage("test"){
            steps{
                echo "code test successfull"
            }
        }
        stage("deploy"){
            steps{
                echo "code deploy successfull"
            }
        }
    }
}
