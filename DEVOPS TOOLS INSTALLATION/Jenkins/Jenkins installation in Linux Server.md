# Login as a root user
```
sudo su -
```
# Install Jenkins
```
cd /opt/

wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo

sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key

yum install jenkins -y
```
Enable and start the jenkins service
```
systemctl enable jenkins

systemctl start jenkins
```
