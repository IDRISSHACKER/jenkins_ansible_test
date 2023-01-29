node{
    stage('Clone project'){
        git 'https://github.com/IDRISSHACKER/jenkins_ansible_test.git'
    }
    stage('Ansible'){
        ansiblePlaybook(
            plabook : './plabook.yml'
        )
    }
}
