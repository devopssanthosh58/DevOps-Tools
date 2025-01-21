
## To install Debian/Ubuntu (LTS)

## Prerequisite for java
```bash
sudo apt install default-jre              # version 2:1.17-75, or
sudo apt install openjdk-17-jre-headless  # version 17.0.12+7-1ubuntu2~24.04
sudo apt install openjdk-21-jre-headless  # version 21.0.4+7-1ubuntu2~24.04
sudo apt install openjdk-19-jre-headless  # version 19.0.2+7-4
sudo apt install openjdk-20-jre-headless  # version 20.0.2+9-1
sudo apt install openjdk-22-jre-headless  # version 22~22ea-1
sudo apt install openjdk-11-jre-headless  # version 11.0.24+8-1ubuntu3~24.04.1
sudo apt install openjdk-8-jre-headless   # version 8u422-b05-1~24.04
```
## Install Jenkins
```bash

sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \ https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \ https://pkg.jenkins.io/debian-stable binary/ | sudo tee \ /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins

```
## Start Jenkins
```bash
sudo systemctl enable jenkins
sudo systemctl start jenkins
sudo systemctl status jenkins
```
If everything has been set up correctly, you should see an output like this:

![output To Attach](https://github.com/devopssanthosh58/DevOps-Tools/blob/main/Jenkins/jenkins.png)

### Install Jenkins to Different flavours Linux Distribution.

[download link](https://www.jenkins.io/doc/book/installing/linux/.)
