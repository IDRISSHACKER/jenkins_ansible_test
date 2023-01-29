node{
    stage('Clone'){
        git 'https://github.com/IDRISSHACKER/jenkins_ansible_test.git'
    }
    stage('Ansible'){
        ansiColor('xterm'){
            ansiblePlaybook(
                colorized: true,
                playbook: './plabook.yml'
            ) 
        }
    }
}
