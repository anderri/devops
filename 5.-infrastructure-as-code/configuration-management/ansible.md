---
description: >-
  Ansible is an open-source software provisioning, configuration management, and
  application-deployment tool enabling infrastructure as code. It runs on many
  Unix-like systems, and can configure both Un
---

# Ansible

### Installation - Mac

{% code title="HomeBrew" %}
```
brew install ansible
```
{% endcode %}



### Installation - Linux

```
sudo yum install epel-release
sudo yum install ansible
```

### Edit Host List

{% code title="Ansible-Server" %}
```
sudo su
vi /etc/ansible/hosts
```
{% endcode %}

Add the ip or host on the file&#x20;

```
//exit sudo 
crtl d
```



### Create SSH Key

{% code title="Ansible-Server" %}
```
cd ~/.ssh
ssh-keygen
```
{% endcode %}

Keys will be created: id\__rsa and id_\_rsa.pub.&#x20;



1. SSH with user and password
2. SSH Keys

###

### Main Commands

Config Host List

```
vim /etc/ansible/hosts 
```

###

### Exercise 1

[http://redhatgov.io/workshops/ansible\_tower\_azure/exercise1.1/](http://redhatgov.io/workshops/ansible\_tower\_azure/exercise1.1/)

### Exercise 2

[https://aap2.demoredhat.com/exercises/ansible\_rhel/1.3-playbook/](https://aap2.demoredhat.com/exercises/ansible\_rhel/1.3-playbook/)



###

### Video

###

### Documentation
