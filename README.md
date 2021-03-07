# Ansible roles for RabbitMQ and Prometheus
## Test environment
```
lsb_release -d
Description:	Ubuntu 20.04.2 LTS
```
```
ansible --version
ansible 2.9.6
  config file = /etc/ansible/ansible.cfg
  configured module search path = ['/home/alexey/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3/dist-packages/ansible
  executable location = /usr/bin/ansible
  python version = 3.8.5 (default, Jan 27 2021, 15:41:15) [GCC 9.3.0]
```
## Usage
* Clone repo
* Modify inventory file
* Run:
```
ansible-playbook -i inventory/test.yml roles.yml
```
