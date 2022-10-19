# Web-Application-Stack-local
### Multi tier web application stack 
Setup on laptop/desktop 
#### Prerequisites 
* Windows 10 or Higher
* Install Chocolatey
* Open Powershell as Administrator
* choco install virtualbox
* choco install vagrant
* choco install git
* choco install jdk8
* choco install maven
* choco install intellijidea-community
* choco install [IDE of your choose]
* vagrant plugin install vagrant-hostmanager
#### Description 
* Deploy 4 Centos VMs and 1 Ubuntu VM with Vagrant multi-machine environment
* First manually provision VMs and then use IAAC to create
  * NginX
  * TomCat
  * RabbitMQ
  * MemCache
  * MySql
  * Finally Deploy Java Application on Tomcat
