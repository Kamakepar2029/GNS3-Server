# GNS3 Server Centos V3
#### Compiled by Kamakepar

## About
Here are some addons. Like enabled sshd, enabled GNS3-Server and custom Working ubridge. Also here is Qemu installed
[![Docker Repo](https://d36jcksde1wxzq.cloudfront.net/be7833db9bddb4494d2a7c3dd659199a.png)](https://hub.docker.com/r/kamakepar/gns3-server-centos-v3)

## How to use it.
FIrst, download it
```
docker pull kamakepar/gns3-server-centos-v3
```
Then run it
```
docker run -it kamakepar/gns3-server-centos-v3
```
Then get the actual ip address
```
ip a | grep inet | awk '{ print $2 }'
```
Second ip will be that you need to connect

## Credentials
#### Login: root
#### Password: root@123

## Modified Packages
* ubridge (from libpcap.so.0.8)
* ssh_hosts_keys (nopassword)
* dynamips (from make)

## Installed packages
* Qemu
* Net-Tools
* GNS3-Server
* Ubridge
* DynamIps
* Vpcs
* Libvirt
* Qemu-Kvm
* vpcs
