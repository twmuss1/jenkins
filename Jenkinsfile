pipeline{
  agent any
  stages{
    stage("execute playbook")
      steps{
        ansiblePlaybook credentialsID: 'jenkins', installation: 'Ansible', inventory: 'ansible/inventories/inventory.yml', playbook: 'main.yml'
      }
  }
}