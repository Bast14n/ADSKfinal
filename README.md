# Ansible automatisation for deploying studentCrud app
<h2>Used technologies</h2>
<br>Telegraf
<br>Ngnix
<br>Grafana
<br>MongoDB
<br>Maven
<br>Java 
<br>SpringBoot
<br>InfluxDB

<h2>Installation:</h2>
<br>- install ansible
<br>- downlad or clone app from https://github.com/Bast14n/studentCrud
<br>- change spring.data.mongodb.host in application.properties
<br>- create package(mvn package)
<br>- change path for generated jar in {{jar_location}} in install.yml
<br>- change path for app in {{app_location}} in install.yml
<br>- change app user in {{app_user}} in install.yml
<br>- change hosts in hosts.ini
<br>- change {{metrics_storage_ip}} in install.yml
<br>- change {{domain}} in install.yml
<br>- change {{server_name}} in install.yml
<br>- change {{domain}} in install.yml
<br>- add private key for server authorization via ssh
<br>- run install.yml using ansible-playbook
