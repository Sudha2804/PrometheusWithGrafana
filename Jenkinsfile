pipeline {
    agent any

    stages {
        stage('Execute playbook') {
            steps {
                sh ' sudo ansible-playbook /etc/ansible/grafana.yml'
            }
        }
    }
}
