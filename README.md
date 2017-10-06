# Docker base install
Install docker on Centos host ( Based on  https://docs.docker.com/engine/swarm/swarm-tutorial/#three-networked-host-machines)
Currently only works on Centos7 (docker Centos6 repos broken )

To use this role add it to one existing playbook

```yaml
- hosts: all
  roles:
     - { role: ansible_docker_ce_centos_install }
 ```


# License

GNU GPLv3

# Author Information

Created by Miguel Rodrigues
