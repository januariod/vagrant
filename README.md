## VAGRANT

### About Vagrant
- Getting started => [vagrantup.com/intro](https://www.vagrantup.com/intro/getting-started)
- Vagrant cloud => [vagrantup.com/boxes](https://app.vagrantup.com/boxes/search)
- Vagrant docs => [vagrantup.com/docs](https://www.vagrantup.com/docs)

### Vagrant Main Commands

#### new vagrantfile
```
vagrant init 'some_machine'
```

#### machine status
```
vagrant status

or

vagrant global status (--prune)
```

#### start
```
vagrant up
```

#### provision
```
vagrant provision
```

#### stop
```
vagrant halt
```

#### reload machine
```
vagrant reload
```

#### destroy/delete
```
vagrant destroy (-f)
```

#### ssh
```
vagrant ssh-config

vagrant ssh

or

vagrant ssh -i 'your_private_key' vagrant@'your_machine'
```

#### list box
```
vagrant box list
```

#### destroy machine
```
vagrant destroy -f
```

### Puppet Main Commands

#### run puppet
```
sudo puppet apply
```

### Ansible Main Commands

#### run ansible
```
ansible-playbook -i /vagrant/configs/ansible/hosts /vagrant/configs/ansible/playbook.yml
```
