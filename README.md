# mac_build
collection of ansible scripts to rebuild a mac and dev environment 

install ansible:

```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

sudo python get-pip.py

sudo pip install ansible
```

run the main playbook: 

```
ansible-playbook main.yaml -i inventory -K
```

