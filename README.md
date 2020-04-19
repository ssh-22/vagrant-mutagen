# vagrant-mutagen

## Objects
This repository is a sandbox of what I learned from the following article.

 [DXを大幅に低下させるDocker for Macを捨ててMac最速のDocker環境を手に入れる](https://qiita.com/yuki_ycino/items/cb21cf91a39ddd61f484)

## Requirements
You need to install the following softwares in advance.
- Vagrant
- VirtualBox

## Install
```sh
git clone https://github.com/ssh-22/vagrant-mutagen.git
```

## SetUp
```sh
vagrant plugin install vagrant-disksize vagrant-hostsupdater vagrant-mutagen
varant up
vagrant ssh
```

## References
- [DXを大幅に低下させるDocker for Macを捨ててMac最速のDocker環境を手に入れる](https://qiita.com/yuki_ycino/items/cb21cf91a39ddd61f484)
- [Vagrantを使う「Mac最速のDocker環境」を初心者向けに解説](https://qiita.com/necocoa/items/bd62ed3dba14b17552f2)
