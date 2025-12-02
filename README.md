# WorkstationConfig

An ansible script to setup my workstation.s

## Prerequisites

In order to run the ansible script, you need to install ansible. Here's the instructions for Ubuntu:
```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```
Then you need to download this repository and run the playbook:
```bash
wget https://github.com/andreaiacono/WorkstationConfig/archive/refs/heads/main.zip
unzip main
cd WorkstationConfig-main
sudo ansible-playbook install.yaml
```

