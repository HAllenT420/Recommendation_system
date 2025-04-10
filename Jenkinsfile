pipeline {
    agent any

    stages {
        stage("Cloning from GitHub...") {
            steps {
                script {
                    echo 'Cloning from GitHub...'
                    checkout([
                        $class: 'GitSCM',
                        branches: [[name: '*/main']],
                        doGenerateSubmoduleConfigurations: false,
                        extensions: [],
                        userRemoteConfigs: [[
                            credentialsId: 'Github-animetoken',
                            url: 'https://github.com/HAllenT420/Recommendation_system.git'
                        ]]
                    ])
                }
            }
        }
    }
}
