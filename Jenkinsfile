node{
    stage('Clone project'){
        git 'https://github.com/IDRISSHACKER/jenkins_ansible_test.git'
    }
    ansiColor('xterm') {
        ansiblePlaybook( 
            playbook: 'playbook.yml',
            inventory: 'hosts', 
            colorized: true) 
    }
}
