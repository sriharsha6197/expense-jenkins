pipeline { 
    agent { node 'terraform'}

    stages {
        stage {'Checking the stage'}
        steps{
            echo 'checking'
            sh 'ansible-playbook jobs.yaml'
        }
    }
}