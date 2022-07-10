### Install

- Clone me and my submodules
```
git clone --recursive https://github.com/eoli3n/arch-config
```
- Install Arch Linux OS, git, openssh, ansible, ansible-core, python-pip, python-virtualenv
  - install ansible modules: ansible-galaxy collections install community.general kewlfft.aur
```sh
ansible-playbook --skip-tags pacman-update ./install.yml # skip-tags is ok if packages have been recently updated
```
- Install packages and configurations with [ansible](ansible/)
- Use [dotfiles](https://github.com/eoli3n/dotfiles)
