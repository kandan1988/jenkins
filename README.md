# Jenkins

For DevOps KT


# To Install Jenkins 

git clone https://github.com/kandan1988/jenkins.git

cd jenkins/jenkins-install

docker-compose up -d


# To Get first time admin password

docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword


# FOr docker Agent change the docker path in the compose file
