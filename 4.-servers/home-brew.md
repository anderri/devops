---
description: Package Manager for macOS and Linu
---

# Home Brew



### Installation

{% code title="brew" %}
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
{% endcode %}

{% code title="mas" %}
```
brew install mas
```
{% endcode %}

{% code title="bundle" %}
```
brew bundle
```
{% endcode %}

### Backup Software List

Create a list of software installed from AppleStore and Terminal Software. Save the file brewfile into your cloud storage.&#x20;

```
brew bundle dump --all --force --describe
```

### Create a Brewfile from all installed packages

```
brew bundle dump
```

### Install packages from a Brewfile at the current path

```
brew bundle
```

### Install packages from a specific Brewfile at a specific path

```
brew bundle --file=[path/to/file]
```



### Uninstall all formulae not listed in the Brewfile

```
brew bundle cleanup --force
```

### Check if there is anything to install or upgrade in the Brewfile

```
brew bundle check
```

### Output a list of all entries in the Brewfile

```
brew bundle list --all
```

### Software Update

```
sudo softwareupdate -ia --verbose ; brew bundle -v ; brew cleanup ; brew doctor --verbose
```

### Update - AppleStore Software

```
mas upgrade
```

### &#x20;Update - Terminal Software

```
brew upgrade
```

### &#x20;Restore Software List&#x20;

```
brew upgrade
```





{% embed url="https://youtu.be/1uvr9-zUB3w?t=47" %}

{% embed url="https://www.youtube.com/watch?t=581s&v=-VP2NVv3LHg" %}

{% embed url="https://www.youtube.com/watch?v=JR3NCh1i4nc" %}



