pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/deepanshuMeteor/qa-121022.git']]])
                }
            }
                
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
                }
            }
        }
}
