# WorkstationConfig

An ansible script to setup my workstation.s

## Prerequisites

In order to run the ansible script, you need to install ansible. Here's the instructions for Ubuntu:
```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible git
```
Then you need to clone this repository:
```bash
git clone git@github.com:andreaiacono/WorkstationConfig.git
```

And finally run the playbook:
```bash
sudo ansible-playbook WorkstationConfig/install.yaml
```
