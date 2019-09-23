# packer build environement for Ubuntu 18.04

This build a QCOW image for ubuntu 18.04 with customization at install or provisioning stage.

```
packer build ubuntu-18.04.json
vagrant box add ubuntu-libvirt.box --name myubuntu
vagrant init myubuntu
vagrant up --provider=libvirt
```