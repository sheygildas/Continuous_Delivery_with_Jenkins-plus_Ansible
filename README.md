
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
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

## :question: Problem that this project solves 

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

## :key: Solution to the problem.

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
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
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>


## :beginner: Architecture of this project.

![Project Image](project-image-url)

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

## :zap: Steps to Execute the project. 

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :key: Login to AWS Account

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :closed_lock_with_key: Create Key Pairs

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :lock: Create Security groups

#### :lock: Jenkins
#### :lock:  Nexus
#### :lock:  SonarQube
<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :bulb: Launch Instances with user data 

#### :bulb: Jenkins
#### :bulb: SonarQube
#### :bulb: Nexus

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :earth_africa: Jenkins Post Installation

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Build Job

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :rocket: Setup Slack Notification

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Checkstyle code analysis Job

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :lock: Setup Sonar integration

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :earth_africa: Sonar code analysis job

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Artifact upload job

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Connect all jobs together with-Build Pipeline

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Set Automatic build trigger

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :hammer_and_wrench: Make Code change

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Create SG

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

#### :package: Windows server

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

#### :package: Tomcat and backend servers

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Setup tomcat and backend server on ec2 with user data

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Create Jenkins Job to Run Ansible Playbook

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Create Jenkins Job to Deploy artifact to Staging using Ansible

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Add windows node as slave to Jenkins

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Create Job to run Software Tests with Selenium from Windows server

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Deploy artifact to Production tomcat server using Ansible

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Connect all the jobs with Build Pipeline

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

### :package: Test it by committing code to github

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>

## :earth_africa: Verify from browser

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>


## :page_facing_up: Resources

<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>


## :star2: Acknowledgment


<br/>
<div align="right">
    <b><a href="#Project-12">??? back to top</a></b>
</div>
<br/>
