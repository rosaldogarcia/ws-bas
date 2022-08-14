@Library("shared-library") _
pipeline {
    agent any 
    stages {
        stage('Example') { 
            steps {
//                sh 'echo hello world'
                helloWorldExternal(rossjs:"True", rosconverters:"True", others:"True")
            }
        }
    }
}
