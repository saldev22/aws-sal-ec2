pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('stage1') {
                        steps {echo 'running stage1'}
        }
    stages {
        stage('stage2') {
                        steps {echo 'running stage2'}
            echo "stage2 finished"
        }
    }
}
}