# This memo is to start vm quickly for my develop environment

* init vm

```
$ mkdir -p ~/Vagrant/cent65
$ cd ~/Vagrant/cent65
$ vagrant init cent65
```

* copy Vagrantfile from target vagrantfile


* start vm

```
$ vagrant up
```

* ssh config to login easily

```
$ vagrant ssh-config --host cent65 > ~/.ssh/config
```

* ssh login

```
$ ssh cent65
```

* switch to root

```
$ su -
Password: vagrant
```
