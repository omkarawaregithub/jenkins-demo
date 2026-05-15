pipeline{
    agent any
    stages{
        stage('clone repository'){
            steps{
                echo 'github token automatically uses git credentials from the Jenkinsfile...'
                git credentialsId: 'github-token', 
                url: 'https://github.com/omkarawaregithub/jenkins-demo.git'
            }
        }
    }
}