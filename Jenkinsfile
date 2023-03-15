pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 20, unit: 'SECONDS')
    }
    stages {
        stage('stage1 test') {
                        steps {echo 'running test'}
        }
        stage('stage2 build') {
                        steps {echo 'running build'}
        }   
        stage('stage2 deploy') {
                        steps {echo "stage2 deploy"}
    }
        stage('finished') {
                        steps {echo 'ec2 build finished'}
        }
}
}