# harden-ubuntu16

* tested for fresh ubuntu 16.04 install on linode, initial lynis score 57
```
apt install git ansible
cd /opt/
git clone https://github.com/edgarmaloverian/harden-ubuntu16.git
cd harden-ubuntu16 
ansible-playbook ./main.yml
```
