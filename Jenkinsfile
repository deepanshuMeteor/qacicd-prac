pipeline{
        agent any
        stages{
            stage('Clone'){
                steps{
                    checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://gitlab.com/qacdevops/chaperootodo_client.git']]])
                }
            }
                
            stage('Install'){
                steps{
                    
                }
            }
                stage('deploy'){
                steps{
                    
                }
            }
        }
}
