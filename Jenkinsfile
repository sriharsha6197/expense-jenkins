pipeline { 
    agent { node 'terraform'}

    stages {
        stage {'Checking the stage'}
        steps{
            echo 'checking'
            ansible-playbook jobs.yaml
        }
    }
}