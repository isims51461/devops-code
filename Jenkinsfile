pipeline{
     agent any
     stages{
       stage('Execute Ansible Playbook'){
         steps{
           ansiblePlaybook credentialsId: 'ansible_user_2', disableHostKeyChecking: true, installation: 'ansible', inventory: 'hosts', playbook: 'test.yml'
         }
       }
     }
}
