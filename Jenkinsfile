pipeline {
    agent any 
    stages {
      stage('ec2 deploy'){
          steps {
	      sh 'cd /var/www/html/'
              sh 'rm -rf *.*'
              sh 'rm -rf .git'
              sh 'git clone https://github.com/MukhtarAbdi/gittest.git'
              sh 'cd gittest'
              sh 'systemctl restart apache2'
          }
       }
    }
  }

