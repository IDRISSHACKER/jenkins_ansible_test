node{
    state('Clone project'){
        git 'https://github.com/IDRISSHACKER/jenkins_ansible_test.git'
    }
    stage('Ansible'){
        ansiblePlaybook(
            plabook : 'plabook.yml',
            inventory : 'hosts',
            vault_password_file : '.vault_pass',
            host_key_checking : False
        )
    }
}
