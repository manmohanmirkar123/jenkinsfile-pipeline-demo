pipeline {
    
    agent any
    
    stages {
        
        stage('build') {
            steps {
                sh '''
                echo "this is building"
                pwd
                #pwd1
                '''
                
            }
        }
        
        stage ('test'){
            steps {
                echo "this is testing"
            }
        }
    }
    post {
        always {
        echo "Always executed"
    }
    success {
        
        echo "executed on success"
    }
    failure {
        echo "executed on failure"
    }
    }
}
