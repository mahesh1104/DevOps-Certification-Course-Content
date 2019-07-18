# DevOps-Certification-Course-Content

Infrastructure Setup

EC2 Walkthrough
Installation of Devops Tools on cloud
Git
Docker
   sudo apt-get remove docker docker-engine docker.io containerd runc
   sudo apt-get update
   sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  sudo apt-key fingerprint 0EBFCD88
  sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
  sudo apt-get update
  sudo apt-get install docker-ce docker-ce-cli containerd.io
  
Selenium
Maven
Jenkins
Puppet
Ansible
Kubernetes
Nagios

-----------------------------------

EC2 Walkthrough
Installation of Devops Tools on cloud
Git
Docker
Selenium
  docker run -d --name se -p 5900:5900  -p 4444:4444 selenium/standalone-firefox-debug
Maven
Jenkins
Puppet
Ansible
Kubernetes
Nagios
