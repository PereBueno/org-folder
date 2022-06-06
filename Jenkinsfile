pipeline {
    agent none    
    stages {
        stage('dummy') {
            steps {
                script {
                    jdkConfig['jdk11'].agentImage.linux = buildDockerImage('jdk11')
                }
            }
        }
    }
}
