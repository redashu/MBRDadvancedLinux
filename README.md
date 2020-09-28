# SSH overview again 

<img src="sshover.png">

## Security of SSH 

### port security 

<b> you can change default port number with selinux rule that we have already seen </b>

###  disable root access 

<img src="noroot.png">

## denyusers in ssh 

<img src="denyuser.png">

# storage sharing understanding 

<img src="storage.png">

## NFS with RPC 

<img src="nfsrpc.png">

## NFS server. install 

<img src="nfsinstall.png">

## nfs server configure

<img src="nfsconf.png">

## loading nfs configuration and starting service

<img src="nfsstart.png">

## nfs client installation and check on opensuse

<img src="nfsclientop.png">


## nfs client installation and check on centos

<img src="nfsclientcentos.png">

## nfs mount on client machine 

<img src="nfsmount.png">


## allow write operation to clients on server side

<img src="nfswrite.png">

## nfs client persistent mount 

<img src="nfsper.png">

##  another mounting 

<img src="mountnfs.png">


## Server configuration updates

<img src="nfsserver.png">


# NFS server On centos 7

##  Install software 

```
yum install nfs-utils -y
```

## configuration file is same as opensuse 

```
cat /etc/exports 

```

## starting. nfs service

```
systemctl start nfs-server
systemctl enable nfs-server

```





