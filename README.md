>#  zero_day 

## Using Vagrant on Local Machine


- Setup Vagrant to emulate the Linux Ubuntu version 5.4.0.113
- Using Virtual box as the provider to manage and ship isolated development environments.

Setting up Vagrant on OSX:

## Setting up Vagrant on OsX :

```
  - Download Virtual box from this [link](https://www.virtualbox.org/wiki/Downloads)
  - Install Virtual box after download
  - Run `brew install Vagrant` on the terminal
  - add image $ vagrant box add ubuntu/focal64
```

## Next Steps:
- Run `brew install Vagrant` on the terminal
- Create Ubuntu image `$ vagrant box add ubuntu/focal64`
- Create a virtual machine `$ vagrant init ubuntu/focal64` N/B: Used only once
- Boot your virtual machine with `vagrant up`
- Type `$ vagrant ssh` to get inside your virtual machine
