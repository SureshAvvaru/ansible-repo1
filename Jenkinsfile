pipeline {
      agent any
      stages {
         stage('dev playbook') {
            steps {
            sh "ansible-playbook newdir/multi.yml -b"
       }
    }
  }
}
