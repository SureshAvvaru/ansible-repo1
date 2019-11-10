pipeline {
      agent {
         node {
           label 'Node-1'
         }
       }
        
      stages {
         stage('dev playbook') {
            steps {
            sh "ansible-playbook newdir/docker.yml -b"
       }
    }
  }
}
