pipeline{
  agent any 
  stages{
    stage('Git Codecheckout'){
      steps{
        script{
             sh " git clone <https://github.com/koneti0021/Ansibleproject.git>"
        }
      }
    }
    stage('Run an ansible playbook'){
      steps{
        script{
           sh "ansible-playbook -i Inventory 02.yml"
        }
      }
    }
  }
}

    
      
