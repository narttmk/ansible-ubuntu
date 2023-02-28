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

### File structure

ansible/
├── roles/
│   ├── aws-cli/
│   ├── chrome/
│   ├── docker/
│   ├── edge/
│   ├── intellij/
│   ├── node/
│   ├── postman/
│   ├── vscode/
│   └── zsh/
└── playbook.yml


### Using
Comment what you don't want to install
![ScreenCapture](/images/capture1.png "Screen Capture")

Using this command to install softwares:

```bash
ansible-playbook playbook.yml
```