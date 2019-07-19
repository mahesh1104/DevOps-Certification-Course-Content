# DevOps-Certification-Course-Content

Infrastructure Setup

EC2 Walkthrough
Installation of Devops Tools on cloud
Git
https://www.youtube.com/watch?v=eEhcPWdAb9Q
https://www.youtube.com/watch?v=rb5OL-QQPw4

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
https://www.youtube.com/watch?v=rb5OL-QQPw4

Maven

Jenkins
https://www.youtube.com/watch?v=8W6gdCwxIsI
Puppet
https://www.youtube.com/watch?v=HFpqosHD7aE
Ansible
 https://www.youtube.com/watch?v=2jBR7fYbfro
Kubernetes
  https://www.youtube.com/watch?v=4ZwmiLGBIR0
  
Nagios
 https://www.youtube.com/watch?v=AkC7dE2AbgY&t=36s

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

htpasswd -c -b /etc/nagios/passwd admin admin

nuagebec/ubuntu

Adding Nagios host

1.Install NRPE server plugin on host
    sudo apt-get update
    sudo apt-get install nagios-nrpe-server nagios-plugins

54.90.191.118
 
2.Configure NRPE
     Update Nagio server address
  vi /etc/nagios/nrpe.cfg
  server_address=

3. 

