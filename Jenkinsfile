node{
    stage('Clone'){
        git 'https://github.com/IDRISSHACKER/jenkins_ansible_test.git'
    }
    stage('Ansible'){
        ansiColor('css'){
            ansiblePlaybook(playbook: './plabook.yml') 
        }
    }
}
