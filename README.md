## ansible-role-tmux

![status](https://travis-ci.org/jamesla/ansible-role-tmux.svg?branch=master)

Builds and installs tmux from the master branch rather than from apt which can be out of date on older distributions.

### Usage

playbook.yml:
```
- { role: ansible-role-tmux }
```

requirements.yml:
```
- src: https://github.com/jamesla/ansible-role-tmux.git
  version: master
  name: ansible-role-tmux
```
