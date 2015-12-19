**info**


```
--network bridge=kvm \ can changed to standard --network bridge=virbr0 \
if nothing is defined default address {virbr0 --> 192.168.122.*}
```

**installation**

```bash
btrfs:
--------
--network bridge=virbr0 --> standard configuration

sudo wget https://raw.githubusercontent.com/DoJoMi/ks_virt/master/centos_btrfs.sh -O - > file &&  sudo sh file centos

uname:dojomi
pwd: dojomi

lvm:
--------
--network bridge=kvm --> own created bridge network

sudo wget https://raw.githubusercontent.com/DoJoMi/ks_virt/master/centos_lvm.sh -O - > file &&  sudo sh file centos

uname:dojomi
pwd: dojomi

```
