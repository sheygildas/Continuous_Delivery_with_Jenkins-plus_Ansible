
# Project-12
## :ledger: Index

- [About The Project](#beginner-about-the-project)
- [Problem that this project solves ](#question-problem-that-this-project-solves)
- [Solution to the problem.](#key-solution-to-the-problem)
- [Tools and Services](#hammer_and_wrench-tools-and-services)
- [Architecture of this project](#house-architecture-of-this-project)
- [Steps to execute the project](#zap-steps-to-execute-the-project)
  - [Login to AWS Account ](#key-login-to-aws-account )
  - [Create Key Pairs](#closed_lock_with_key-create-key-pairs)
  - [Create Security groups](#lock-create-security-groups)
    - [Jenkins](#lock-jenkins)
    - [Nexus](#lock-nexus)
    - [SonarQube](#lock-sonarqube)
  - [Launch Instances with user data](#bulb-launch-instances-with-user-data )
    - [Jenkins](#lock-jenkins)
    - [Nexus](#lock-nexus)
    - [SonarQube](#lock-sonarqube)
  - [Jenkins Post Installation](#earth_africa-jenkins-post-nstallation)
  - [Build Job](#hammer_and_wrench-build-job)
  - [Setup Slack Notification  ](#rocket-setup-slack-notification )
  - [Checkstyle code analysis Job](#package-checkstyle-code-analysis-job)
  - [Setup Sonar integration ](#lock-setup-sonar-integration)
  - [Sonar code analysis job](#earth_africa-sonar-code-analysis-job)
  - [Artifact upload job](#hammer_and_wrench-artifact-upload-job)
  - [Connect-all-jobs-together-with-Build-Pipeline](#hammer_and_wrench-connect-all-jobs-together-with-build-pipeline)
  - [Set Automatic build trigger](#hammer_and_wrench-set-utomatic-build-trigger)
  - [Make Code change](#hammer_and_wrench-make-code-change)
  - [Create SG](#package-create-sg)
    - [Windows server](#package-windows-server)
    - [Tomcat and backend servers](#package-tomcat-and-backend-servers)
  - [Setup tomcat and backend server on ec2 with user data](#package-setup-tomcat-and-backend-server-on-ec2-with-user-data)
  - [Create Jenkins Job to Run Ansible Playbook](#package-create-jenkins-job-to-run-ansible-playbook)
  - [Create Jenkins Job to Deploy artifact to Staging using Ansible](#package-create-jenkins-job-to-deploy-artifact-to-staging-using-ansible)
  - [Add windows node as slave to Jenkins](#package-add-windows-node-as-slave-to-jenkins)
  - [Create Job to run Software Tests with Selenium from Windows Server](#package-create-job-to-run-software-tests-with-selenium-from-windows-server)
  - [Deploy artifact to Production tomcat server using Ansible](#package-deploy-artifact-to-production-tomcat-server-using-ansible)
  - [Connect all the jobs with Build Pipeline](#package-connect-all-the-jobs-with-build-pipeline)
  - [Test it by committing code to github](#package-test-it-by-committing-code-to-github)
 - [Verify from browser](#earth_africa-verify-from-browser) 
 - [Resources](#page_facing_up-resources)
 - [Credit/Acknowledgment](#star2-creditacknowledgment)


## :beginner:About The Project

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

## :question: Problem that this project solves 

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

## :key: Solution to the problem.

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

## :hammer_and_wrench: Tools and Services
- visual studio code or an IDE
- AWS Account
- Nexus
- SonarQube
- Slack
- Maven
- JDK8
- Github Account

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>


## :beginner: Architecture of this project.

![Project Image](project-image-url)

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

## :zap: Steps to Execute the project. 

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :key: Login to AWS Account

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :closed_lock_with_key: Create Key Pairs


<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :lock: Create Security groups

#### :lock: Jenkins
#### :lock:  Nexus
#### :lock:  SonarQube
<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :bulb: Launch Instances with user data 

#### :bulb: Jenkins
#### :bulb: SonarQube
#### :bulb: Nexus

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :earth_africa: Jenkins Post Installation

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Build Job

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :rocket: Setup Slack Notification

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Checkstyle code analysis Job

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :lock: Setup Sonar integration

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :earth_africa: Sonar code analysis job

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Artifact upload job

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Connect all jobs together with-Build Pipeline

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Set Automatic build trigger

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Make Code change

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Create SG

- Create two security group for the Windows server and Tomcat and backend servers


<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

#### :package: Windows server

- On your console under `EC2`-> `security group` click `create security group`.
- Create a security group for the `Windows server` with the following details.

```sh
Name: Windows-Server-SofTest
Description: Windows-Server-SofTest
Tag: Windows-Server-SofTest
Allow: RDP from MYIP
Allow: all traffic from vprofile-jenkins-sg

   ```


<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

#### :package: Tomcat and backend servers

- On your console under `EC2`-> `security group` click `create security group`.
- Create a security group for `Tomcat` with the following details.

```sh
Nam1e: vprofile-app-staging-sg
Description: vprofile-app-staging-sg
Tag: vprofile-app-staging-sg
Allow: 8080 from MY IP 
Allow: port 22 from Anywhere from MY IP
Allow: port 22 from vprofile-jenkins-sg
Allow: 8080 from Windows-Server-SofTest
Allow: RDP from MYIP
Allow: all traffic from vprofile-jenkins-sg

   ```
   
- On your console under `EC2`-> `security group` click `create security group`.
- Create a security group for `Backend services` with the following details.

```sh
Name: vprofile-be-staging-sg
Description: vprofile-be-staging-sg
Tag: vprofile-be-staging-sg
Allow: all traffic from vprofile-app-staging-sg
Allow: port 22 from MY IP 

   ```

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Setup tomcat and backend server on ec2 with user data

- On your console under EC2->Instances click launch instances.
- We will create `Tomcat` with below details.


```sh
Name: Tomcat-server
AMI: Ubuntu 20.04
SecGrp: vprofile-app-staging-sg
InstanceType: t2.small
Tga: app01-staging-vprofile
KeyPair: ci-vprofile-key

   ```
   
   
- On your console under EC2->Instances click launch instances.
- We will create Backend-server with below details.


```sh
Name: Backens-Server
AMI: centos 7
SecGrp: vprofile-be-staging-sg
InstanceType: t2.small
Tga: be01-staging-vprofile
Userdata: use the userdata given below.
KeyPair: ci-vprofile-key

   ```
   
- Use the script below as userdata to launch our backend services


```sh
#!/bin/bash
DATABASE_PASS='admin123'
yum update -y
yum install epel-release -y
yum install mariadb-server -y
yum install wget git unzip -y

#mysql_secure_installation
sed -i 's/^127.0.0.1/0.0.0.0/' /etc/my.cnf

# starting & enabling mariadb-server
systemctl start mariadb
systemctl enable mariadb

#restore the dump file for the application
cd /tmp/
wget https://raw.githubusercontent.com/devopshydclub/vprofile-repo/vp-rem/src/main/resources/db_backup.sql
mysqladmin -u root password "$DATABASE_PASS"
mysql -u root -p"$DATABASE_PASS" -e "UPDATE mysql.user SET Password=PASSWORD('$DATABASE_PASS') WHERE User='root'"
mysql -u root -p"$DATABASE_PASS" -e "DELETE FROM mysql.user WHERE User='root' AND Host NOT IN ('localhost', '127.0.0.1', '::1')"
mysql -u root -p"$DATABASE_PASS" -e "DELETE FROM mysql.user WHERE User=''"
mysql -u root -p"$DATABASE_PASS" -e "DELETE FROM mysql.db WHERE Db='test' OR Db='test\_%'"
mysql -u root -p"$DATABASE_PASS" -e "FLUSH PRIVILEGES"
mysql -u root -p"$DATABASE_PASS" -e "create database accounts"
mysql -u root -p"$DATABASE_PASS" -e "grant all privileges on accounts.* TO 'admin'@'localhost' identified by 'admin123'"
mysql -u root -p"$DATABASE_PASS" -e "grant all privileges on accounts.* TO 'admin'@'%' identified by 'admin123'"
mysql -u root -p"$DATABASE_PASS" accounts < /tmp/db_backup.sql
mysql -u root -p"$DATABASE_PASS" -e "FLUSH PRIVILEGES"

# Restart mariadb-server
systemctl restart mariadb
# SETUP MEMCACHE
yum install memcached -y
systemctl start memcached
systemctl enable memcached
systemctl status memcached
memcached -p 11211 -U 11111 -u memcached -d
sleep 30
yum install socat -y
yum install wget -y
wget https://www.rabbitmq.com/releases/rabbitmq-server/v3.6.10/rabbitmq-server-3.6.10-1.el7.noarch.rpm
rpm --import https://www.rabbitmq.com/rabbitmq-release-signing-key.asc
yum update
rpm -Uvh rabbitmq-server-3.6.10-1.el7.noarch.rpm
systemctl start rabbitmq-server
systemctl enable rabbitmq-server
systemctl status rabbitmq-server
echo "[{rabbit, [{loopback_users, []}]}]." > /etc/rabbitmq/rabbitmq.config
rabbitmqctl add_user test test
rabbitmqctl set_user_tags test administrator
systemctl restart rabbitmq-server



   ```
   
   
<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Create Jenkins Job to Run Ansible Playbook

- `SSH` into your jenkins ubuntu machine and install ansible usign the the command below.

```sh
sudo apt update
sudo apt-add-repository ppa:ansible/ansible
sudo apt install ansible
   ```
   

- Get your jenkins public ip from the jenkins instance running on your AWS console.
- Open your browser and enter `jenkins public IP` on your url. Login into your Jenkins server using your credential. 
- On your jenkins goto `Manage jenkins`-> `manage plugins` and install a plugin called `ansible`
- After installing the plugin, create a job by going to `New Item` and use the following detals.


```sh
Item name: Deploy-To-Staging
Scroll down and copy it from Build Job that was created earlier.
Change the branch to cd-ansible-jenkins 
   ```
- RUN this job. After running the job, open the job and goto `configure` and macke the following changes to the job.


```sh
Add Build step: invoke ansible playbook
Playbook path: ansible/site.yml

inventory content: app01-staging ansible_host =<private IP of tomcat server on aws>
[appsrvgrp]
app01-staging 

Add credentials: 
kind=username with privatwe key
ID= app-staging-ssh-login
username: ubuntu
Key: copy the private of ci-vprofile-key and paste it

Add extra vaiables:
key:USER
value:admin
key:PASS
value:admin123
key:nexusip
value: <private ip of nexus server on aws>
key:reponame
value:vprofile-release
key:groupid
value: QA
key:time
value:$TIME
key:BUILD
value:$ID
key:vprofile_version
value:$TIME-$DI.var
On you jenkins configure, scroll up and sellect this project is parametarize.
Add parameter: 
Name: TIME
Name: ID
save the changes
   ```
   
   
<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Create Jenkins Job to Deploy artifact to Staging using Ansible
- On your Jenkins open the `Deploy-to-nexus` job click on `configure` and make the following changes.


```sh
Scroll down to Build
Under nexus details, change the:
version to $BUIL_IB
Artifactid to $BUILD_TIMESTAMP 
   ```
- Edit `vprofile-nexus-sg` security group to allow port 8081 from vprofile-app-staging-sg security group-
- Save and RUN the `Deploy-to-nexus` job
- After that RUN the ` Deploy-To-Staging` job. Provide the TIME and ID parameters, these parameters are found on the release artifact on the nexus repository.

- We have to change the branch of the jenkins project the we created earlier in our continoue intergrateion project.

- On your Jenkins open the `Build` job click on `configure` and make the following changes.


```sh
Scroll down to Source Code Management
Branch Specifier: */cd-ansible-jenkins
   ```

- On your Jenkins open the `Code Analysis` job click on `configure` and make the following changes.


```sh
Scroll down to Source Code Management
Branch Specifier: */cd-ansible-jenkins
   ```

- On your Jenkins open the `Integration Test` job click on `configure` and make the following changes.


```sh
Scroll down to Source Code Management
Branch Specifier: */cd-ansible-jenkins
   ```
   
- On your Jenkins open the `Test` job click on `configure` and make the following changes.


```sh
Scroll down to Source Code Management
Branch Specifier: */cd-ansible-jenkins
   ```

- On your Jenkins open the `SonarScanner-CoddAnalysis` job click on `configure` and make the following changes.


```sh
Scroll down to Source Code Management
Branch Specifier: */cd-ansible-jenkins
   ```


- On your Jenkins open the `Build` job click on `configure` and make the following changes.This script will update our application.properties file to connect to our database

- Rplace db01 on the script below with the private ip of your database on AWS 
- 
```sh
Scroll down to Build
execute shell: copy and paste the cript below.

cat << EOT > src/main/resouces/application.properties

#JDBC Configutation for Database Connection
jdbc.driverClassName=com.mysql.jdbc.Driver
jdbc.url=jdbc:mysql://db01:3306/accounts?useUnicode=true&characterEncoding=UTF-8&zeroDateTimeBehavior=convertToNull
jdbc.username=admin
jdbc.password=admin123

#Memcached Configuration For Active and StandBy Host
#For Active Host
memcached.active.host=mc01
memcached.active.port=11211
#For StandBy Host
memcached.standBy.host=127.0.0.2
memcached.standBy.port=11211

#RabbitMq Configuration
rabbitmq.address=rmq01
rabbitmq.port=5672
rabbitmq.username=test
rabbitmq.password=test

#Elasticesearch Configuration
elasticsearch.host =192.168.1.85
elasticsearch.port =9300
elasticsearch.cluster=vprofile
elasticsearch.node=vprofilenode
EOT

   ```
   

- On your Jenkins open the `Codd Analysis` job click on `configure` and make the following changes.


```sh
Scroll down to post build action
report violation
checkstyle  ncrease it to 10, 1000, 100
   ```
   

- Login into your sonarqube server through the browser using the public IP of your sonarqube server. Set the `quality gates` to 1000


- On your Jenkins open the `Deploy-to-Nexus` job click on `configure` and make the following changes.


```sh
Scroll down to post build action
Add post buil action
select trigger parameterze build on other projects 
project to build : Deploy-To-Staging-Ansible 
Add parameters 
TIME= $BUILD_TIMEstamp
ID=$BUILD_ID
SAVE CHANGES
   ```
   
- Create a new view and called it vprofile-continous-delivery click pipeline view then  ok

- On edit view enter the following details 

```sh
initial job: Build 
click ok
   ```
   
- Now RUN your new view pipeline 

- Check whether the deployment completed successfully by copying the public IP of our application server on aws and pasting it on your url.
- 
- Also login and try testing your database 
   
<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Add windows node as slave to Jenkins

- Let's launch our windows server instance 
- On your console under EC2->Instances click launch instances.
- We will create Jenkins-server with below details.

```sh
Name: Windows-server
AMI:   server 2019 base
SecGrp: Windows-Server-SofTest
InstanceType: t2.small
Userdata: use the userdata given below
KeyPair: ci-vprofile-key

   ```
   
```sh
<powershell>
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
choco install jdk8 -y 
choco install maven -y 
choco install googlechrome -y
choco install git -y
mkdir C:\jenkins
</powershell>

   ```
   
- Add a rule to jenkins secuirty group to allow all from windows server security group
- On the AWS console. select your Windows server then click `connect` -> `RDP Client`- > `Get password`. Now upload your private key of ci-vprofile-key
- Click on decrypt password to get your password.
- Now RDP into your intances using th public IP of the windows server. Enter your credentials to login into the server 

- Open your browser and enter `jenkins public IP` on your url. Login into your Jenkins server using your credential. 
- On your jenkins goto `Manage jenkins`-> `configure system` and give the details below


```sh
Jenkins URL: http://<JNKINS PRIVATE IP>/8080/
Save changes
   ```
   
- On your jenkins goto `Manage jenkins`-> `Manage Nodes and Clouds` and give the details below


```sh
Name: vprofile-softwareTest
select parmanent agent 
click ok
Remote root directory: c/jenkins
launch method: launch agent by connecting it to the master 
custom work directory: c/jenkins
select use socket 
Save changes
   ```

- On your jenkins goto `Manage jenkins`-> `configure global security` and give the details below


```sh
scroll down to Agent
TCP port for inbound agent: select fixed and enter 8090
Save changes
   ```
   
- On your jenkins goto `Manage jenkins`-> `Manage Nodes and Clouds` and copy the `run agent from command line` command and goto your CMD  ns run the command.
- Now our windows server is connected as a slave.

   
<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Create Job to run Software Tests with Selenium from Windows server

- On your jenkins goto `New Item` create a job and give the details below

```sh
Item name: Software-Testing
Under general, select retrict where this project can run the put vprofile_softwareTest-Node
Scroll down and copy it from Build Job that was created earlier.
Change the branch to */seleniumAutoScripts 
Revove the execute shell script
Remove the archive artifact 
remove build other project 
Invoke top level maven target 
Goals: clean, test -Dsurefir.suiteXmlFiles=testing.xml -Durl=http://<public IP of app01>:8080/login -Dusr=admin_vp -Dpass=admin_vp -DsShotPath=C:\\jenkins\\screnshots
Save changes
   ```
- RUN the job. This job will automatically login to our windows server, take the screenshot of the login page of our app and store it in jenkins server windows server as well .



- On your Jenkins open the `Deploy-To-Staging-Ansible` job click on `configure` and make the following changes.


```sh
Scroll down to post build action
Add post buil action
select trigger parameterze build on other projects 
project to build : Sotfware-Testing  
Add parameters 
TIME= $TIME
ID=$ID
SAVE CHANGES
   ```
   
<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Deploy artifact to Production tomcat server using Ansible

- On your console under EC2->Instances click launch instances.
- We will create `production` server with below details.


```sh
Name:   Production server
AMI: Ubuntu 20.04
SecGrp: vprofile-app-staging-sg
InstanceType: t2.small
Tga: app01-staging-vprofile
KeyPair: ci-vprofile-key

   ```
- On your jenkins goto `New Item` create a job and give the details below

```sh
Item name: Deploy-To-Prod-ansible
Scroll down and copy it from Deploy-To-Staging-Ansible Job that was created earlier.
Change the inventory content: app01-staging ansible_host =<private IP of production server on aws>
[appsrvgrp]
app01-Prod 
Remove trigger parameterze build on other projects 
Remove project to build : Sotfware-Testing  
Save changes
   ```

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Connect all the jobs with Build Pipeline


- On your Jenkins open the `Sotfware-Testing` job click on `configure` and make the following changes.


```sh
Scroll down to post build action
Add post buil action
select trigger parameterze build on other projects 
project to build : Deploy-To-Prod-Ansible 
Add parameters 
TIME= $BUILD_TIMEstamp
ID=$BUILD_ID
SAVE CHANGES
   ```

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

### :package: Test it by committing code to github
- Make some cose changes on your ReadMe.md file commit it to github and watch the pipeline get triggered automatically 
- 
<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>

## :earth_africa: Verify from browser

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>


## :page_facing_up: Resources

<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>


## :star2: Acknowledgment


<br/>
<div align="right">
    <b><a href="#Project-12">↥ back to top</a></b>
</div>
<br/>
