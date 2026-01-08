pipeline {
    agent any 
      stages {
        stage('get the code') { 
            steps {
               git credentialsID: 'github-creds',
               url: 'https://github.com/rajith1298/jenkins-repo'
               branch: 'master'
            }
        }
    }
}
