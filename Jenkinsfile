pipeline {
      agent any
      stages {
         stage('dev playbook') {
            steps {
          sh 'ansible-playbook testingdir/nginx.yml -b'
       }
    }
}
