pipeline {
      agent any
      stages {
         stage('dev playbook') {
            steps {
            sh "ansible-playbook multi.yml -b"
       }
    }
  }
}
