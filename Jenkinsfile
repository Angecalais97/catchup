pipeline {
    agent {
        label 'agent1'
    }
    
    stages {
        stage ('hello') {
            steps {
                echo 'hello world'
            }
        }
        
        stage ('pwd') {
            steps {
                sh '''
                pwd
                touch pipeline
                '''
                
            }
        }
        
       
    }
}

