pipeline{
    agent any
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
        stage('test'){
            agent {label 'master'}
            steps {
                script{
                    sh "echo hi hello"
                }
            }
        }
    }
}
    
