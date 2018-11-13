<link rel="stylesheet" type="text/css" media="all" href="css/markdown.css" />

<center>

# Archlinux Installation
## #Updates #CodeImprovment #ComingSoon

Install and configure archlinux has never been easier!

Try also with :
`VIRTUALBOX` & `VMWARE`

Need :
internet connection & login as `root`

## Download
#### By Git 

    1. mount -o remount,size=2G /run/archiso/cowspace
    2. pacman -Sy git
    3. git clone git://github.com/XEmpty/ArchInstall

#### By Wget & Increase Cowspace

    1. mount -o remount,size=2G /run/archiso/cowspace
    2. wget https://github.com/XEmpty/ArchInstall/tarball/master -O - | tar xz

### How to use
  
    PreInstall : cd <repo_name> && ./preinstall
    PostInstall : cd <repo_name> && ./postinstall

</center>