Video for creation of Ec2 instance and installation of
- git
- Java
- Jenkins

Video Link:

https://vimeo.com/825815693/fd44780c35

Commands for installtion of Git
# sudo su -
# yum install git -y

Command to install java and jenkins:

# sudo su -
# sudo amazon-linux-extras install java-openjdk11 -y
# sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
# sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
# yum install jenkins -y

===========================================================================
