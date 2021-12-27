# Ansible System Setup

Repository to bootstrap and setup my laptop and other machines.

This repository is based on the design
[here](https://github.com/LearnLinuxTV/personal_ansible_desktop_configs) and
[this tutorial](https://www.youtube.com/watch?v=gIDywsGBqf4)


## Bootstrap

The bootstrap script is all that is required to install and set everything up.

```bash
wget http://raw.githubusercontent.com/punchagan/ansible-system-setup/main/bootstrap -O /tmp/install.sh; bash /tmp/install.sh
```
