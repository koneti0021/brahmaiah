pipeline{
    agent master
    stages{
        stage('codecheckout'){
            agent {label 'master'}
            steps {
                script{
                    sh "echo hi hello how are you"
                }
            }
        }
        stage('build'){
            agent {label 'master'}
            steps {
                script{
                    sh "echo hi hello"
                }
            }
        }
    }
}
    
