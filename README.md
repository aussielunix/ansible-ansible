# Ansible Role - ansible

![Build Status](https://circleci.com/gh/aussielunix/ansible-ansible/tree/master.svg?style=shield&circle-token=af1c34bff05f50824300dc8b436b9e0a6bd564da "CircleCI Build Status")

This role will ensure that ansible and all dependencies are installed and ready for use.  

## Requirements

`python`

## Role Variables

none

## Dependencies

None

## Example Playbook

```
- hosts: all
  roles:
     - aussielunix.ansible
```
## Hacking

There is an included Vagrant setup for hacking on this module.  

```
cd tests
source .hack.sh
vagrant up
ansible-playbook test.yml
...
vagrant destroy
vagrant up
ansible-playbook test.yml -vvvv
...
```

## License

BSD

## Author Information

Mick Pollard  
@aussielunix (twitter, gmail, github, linkedin)