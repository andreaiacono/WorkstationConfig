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
Be sure to follow the post-install instructions that you'll find on your terminal.

You might want to install additional stuff like:

- JetBrains Toolbox: https://www.jetbrains.com/toolbox-app/
- VS Code: https://code.visualstudio.com/docs/?dv=linux64_deb
- JetBrains Mono Font: https://www.jetbrains.com/lp/mono/
- SDKMAN! curl -s "https://get.sdkman.io" | bash ; source "~/.sdkman/bin/sdkman-init.sh"
