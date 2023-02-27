# Using ansible to setup local machine

### Install ansible

```bash
sudo apt-add-repository ppa:ansible/ansible
```

```bash
sudo apt update
```

```bash
sudo apt install ansible
```


### Run playbooks

```bash
ansible-playbook --ask-become-pass --become-user <your_username> playbooks/*
```