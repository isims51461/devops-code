pipeline {
    agent any
    ansiblePlaybook become: true, credentialsId: 'ansible_user_2', disableHostKeyChecking: true, inventory: '/etc/ansible/hosts', limit: 'k8s', playbook: '/etc/ansible/test.yml', sudo: true
