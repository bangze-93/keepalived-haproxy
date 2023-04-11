## Configure HAProxy x Keepalived x Nginx on Docker with Ansible on Ubuntu
#### Replace with your environtment
- IP virtual = 192.168.200.36
- IP keepalived1 = 192.168.200.37
- IP keepalived2 = 192.168.200.38
- IP webserver1 = 192.168.200.39
- IP webserver2 = 192.168.200.40
- Interface = enp0s3

#### Run this command
``` bash
ansible-playbook -i hosts playbook.yml --user ubuntu
``` 
replace user [ubuntu] with your server user 
#### Open your favorite browser and access
http://192.168.200.36
