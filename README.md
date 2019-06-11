# ansible-hands-on
## 01
```
ansible -i inventories/echo_sample.txt default -u ubuntu -m shell -a 'echo "YOUR_NAME">>/home/ubuntu/ansible.log'
```

## 02
```
./inventories/ec2.py --list

ansible-playbook -i inventories/ec2.py servers/apt.yml
```

## 03
```
ansible-playbook -i inventories/ec2.py servers/nginx.yml
```

## 04
```
ansible-vault create vaults/YOUR_FILE.yml
ansible-vault edit vaults/YOUR_FILE.yml
ansible-vault view vaults/YOUR_FILE.yml
```
