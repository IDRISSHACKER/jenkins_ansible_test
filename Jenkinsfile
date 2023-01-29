node{
    stage('Clone'){
        git 'https://github.com/IDRISSHACKER/jenkins_ansible_test.git'
    }
    stage('Ansible'){
        wrap([$class: 'AnsiColorBuildWrapper', colorMapName: "xterm"]) {
            ansiblePlaybook(playbook: './plabook.yml') 
        }
    }
}
