pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 20, unit: 'SECONDS')
    }
    stages {
        stage('stage1') {
                        steps {echo 'running stage1'}
        }
        stage('stage2') {
                        steps {echo 'running stage2'}
        }   
        stage('stage2-complete') {
                        steps {echo "stage2 finished"}
    }
 stages {
        stage('stage 3') {
                        steps {echo 'running stage3'}
        }
 }
}
}