@Library("shared-library") _
pipeline {
    agent any 
    stages {
        stage('Example') { 
            steps {
//                sh 'echo hello world'
                helloWorldExternal(dayOfWeek:"Thursday", name:"Ross")
            }
        }
    }
}
