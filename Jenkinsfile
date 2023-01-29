node{
    stage('Clone project'){
        git 'https://github.com/IDRISSHACKER/jenkins_ansible_test.git'
    }
    ansiColor('xterm') {
        ansiblePlaybook( 
            playbook: './jenkins_ansible_test/playbook.yml',
            inventory: './jenkins_ansible_test/hosts', 
            colorized: true) 
    }
}
