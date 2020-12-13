pipeline{
     agent any
     stages{
       stage('Execute Ansible Playbook'){
         steps{
           ansiblePlaybook become: true, credentialsId: 'ansible_user_2', disableHostKeyChecking: true, installation: 'ansible', inventory: '/etc/ansible/hosts', playbook: 'etc/ansible/test.yml', sudo: true
         }
       }
     }
}
