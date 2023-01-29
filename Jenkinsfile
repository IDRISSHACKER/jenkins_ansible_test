node{
    stage('Ansible'){
        ansiblePlabook {
            plabook: 'plabook.yml',
            inventory : './hosts'
            vault_password_file : './.vault_pass'
            host_key_checking : False
        }
    }
}
