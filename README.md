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
<br>
![image](https://github.com/SiwakornEDZ/Devops-Jenkens-aws-docker-argo-cd/assets/87377798/dcab7539-0c96-49ec-a161-c577a00a9aad)
<br>

![image](https://github.com/SiwakornEDZ/Devops-Jenkens-aws-docker-argo-cd/assets/87377798/906db132-1d07-46bd-b332-c59e1d184eb7)
<br>

![image](https://github.com/SiwakornEDZ/Devops-Jenkens-aws-docker-argo-cd/assets/87377798/cd50c4fe-f4fe-45b8-bc29-81df8b3e6d22)
<br>

![image](https://github.com/SiwakornEDZ/Devops-Jenkens-aws-docker-argo-cd/assets/87377798/8c64b595-d4a4-4e89-ade4-fd49754ef558)
<br>

![image](https://github.com/SiwakornEDZ/Devops-Jenkens-aws-docker-argo-cd/assets/87377798/2749825f-419b-4959-a56d-63826f4b8844)
<br>

![image](https://github.com/SiwakornEDZ/Devops-Jenkens-aws-docker-argo-cd/assets/87377798/a94807e9-836d-4905-9844-d9430cc58d94)









    
  
