---
description: Tool for building and managing virtual machine environments
---

# Vagrant

### Install Vagrant

{% code title="MacOS+Brew" %}
```
brew install vagrant
```
{% endcode %}

### VM Repository

[https://app.vagrantup.com/boxes/search](https://app.vagrantup.com/boxes/search)\\



### Main Commands

**Create a folder**

{% code title="Example" %}
```
cd ~/Document
mkdir Vagrant
cd Vagrant
mkdir WebServer
```
{% endcode %}

**Create a Vagrant file**

{% code title="Centos" %}
```
cd ~/Documents/Vagrant/WebServer
vagrant init centos/7 
```
{% endcode %}

{% code title="WindowsServer2012r2" %}
```
cd ~/DocumentsVagrant/WindowsServer
vagrant init gusztavvargadr/windows-server
```
{% endcode %}

**Enable Public Network**&#x20;

```
cd ~/Documents/Vagrant/Centos
vi Vagrantfile
```

Remove #&#x20;

****<img src="../../.gitbook/assets/Screen Shot 2022-05-10 at 6.15.53 pm.png" alt="" data-size="original">****

**Start VM**

```
vagrant up
```

**Connect**

```
vagrant ssh
```

**Shutdown (Halt)**

```
vagrant halt
```

**Delete**

```
vagrant destroy
```



{% embed url="https://www.youtube.com/watch?v=VRzjkUJz-9U" %}
