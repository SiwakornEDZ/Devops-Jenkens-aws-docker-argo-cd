# Devops-Jenkens-aws-docker-argo-cd
* setup aws ec2 instances
* export ssh "name".pem
* set up ssh
* Host name
*    HostName ipv4
*    User 'name-lowerString'
*    IdentityFile C:\Users\sasa5\Downloads\Linux-VM-Key-6.pem
* sudo apt update
* sudo apt upgrade
* ![image](https://github.com/SiwakornEDZ/Devops-Jenkens-aws-docker-argo-cd/assets/87377798/f3e4a90c-5f08-4287-816f-6cef5ef99890)setup ip jenkins
* sudo apt install openjdk-17-jre
## Install Jenkins
`Refer--https://www.jenkins.io/doc/book/installing/linux/
curl -fsSL https://pkg.jenkins.io/debian/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins` 

$ sudo systemctl enable jenkins       //Enable the Jenkins service to start at boot

$ sudo systemctl start jenkins        //Start Jenkins as a service

$ systemctl status jenkins



    
  
