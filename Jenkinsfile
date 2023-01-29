node{
    stage('Clone'){
        git 'https://github.com/IDRISSHACKER/jenkins_ansible_test.git'
    }
    stage('Ansible'){
        ansiblePlaybook(
            colorized: true,
            playbook: './plabook.yml'
        ) 
    }
}
