pipeline{
    agent any


    stages{
        stage("Cloning from Github..."){
            steps{
                scripts{
                    echo 'Cloning from Github'
                    checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'Github-animetoken', url: 'https://github.com/HAllenT420/Recommendation_system.git']])
                }
            }
        }
    }
}