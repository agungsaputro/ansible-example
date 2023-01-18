### Refrensi

add host in the /etc/ansible/hosts
```
[srv1]
172.16.35.77 ansible_ssh_pass=petruk123 ansible_ssh_user=petruk
```
sesuaikan user di inventory/hosts.yaml dengan yang dilangkah sebelumnya
```
all:
  hosts:
    srv1:
```

https://graspingtech.com/install-docker-ansible/

https://elasticskills.dev/post/install-docker-and-docker-compose-ansible-ubuntu/