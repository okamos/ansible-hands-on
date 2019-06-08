# ansible-hands-on
## 01
```
ansible -i inventories/echo_sample.txt default -u ubuntu -m shell -a 'echo "YOUR_NAME">>/home/ubuntu/ansible.log'
```
