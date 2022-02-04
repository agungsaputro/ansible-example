# ansible-example

ansible-version
```
ansible [core 2.12.2]
  config file = /etc/ansible/ansible.cfg
  configured module search path = ['/home/agungds/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python3/dist-packages/ansible
  ansible collection location = /home/agungds/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/bin/ansible
  python version = 3.8.10 (default, Nov 26 2021, 20:14:08) [GCC 9.3.0]
  jinja version = 2.10.1
  libyaml = True

```
install docker-sdk in server host
```
pip3 install docker
```
edit /etc/ansible/hosts
```
#name grup server
[group_server]
IP_Server ansible_user=root

[group_server:vars]
ansible_python_interpreter=/usr/bin/python3
```
ansible playbook
```
ansible-playbook {file}.yaml
```
