## Configure HAProxy x Keepalived x Nginx on Docker with Ansible on Ubuntu
#### Replace with your environtment
- IP virtual = 192.168.1.121
- IP keepalived1 = 192.168.1.101
- IP keepalived2 = 192.168.1.102
- IP webserver1 = 192.168.1.103
- IP webserver2 = 192.168.1.104
- Interface = enp0s3

#### Run this command
``` bash
ansible-playbook -i hosts playbook.yml --user ubuntu
``` 
replace [user] with your server user that has sudo privillage
#### Open your favorite browser and access
http://192.168.1.121
