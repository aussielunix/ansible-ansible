# Ansible Role - ansible

This role will ensure that ansible and all dependencies are installed and ready for use.  

## Requirements

`python`

## Role Variables

none

## Dependencies

[aussielunix.python](https://galaxy.ansible.com/list#/roles/4845)

## Example Playbook

```
- hosts: all
  roles:
     - aussielunix.python
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
