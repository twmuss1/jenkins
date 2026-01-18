pipeline{
  agent any
  stages{
    stage("execute playbook"){
      steps{
        ansiblePlaybook credentialsId: 'jenkins', installation: 'Ansible', inventory: 'ansible/inventories/inventory.yml', playbook: 'main.yml'
      }
  }
}
}