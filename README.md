# ansible-nginx-api-test


## How to run docker services in VM ?

1. prerequisite - install vagrant, ansible and oracle virtual box on host machine.

```
ansible-galaxy collection install -r requirements.yml 
vagrant up
```

2. edit `/etc/hosts` on host

```
192.168.56.10 nginx.test
```

