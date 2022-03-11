pipeline {
    agent any 
    stages {
      stage('ec2 deploy'){
          steps {
	      sh 'cd /var/www/html/'
              sh 'systemctl restart apache2'
          }
       }
    }
  }

