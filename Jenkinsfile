pipeline{
    agent any
    stages{
        stage('code checkout'){
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
    
