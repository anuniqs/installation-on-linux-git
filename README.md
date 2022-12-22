### RHEL / CentOS Installation,

#### YUM installation

`[root@c7-54-git ~]# yum update`

`[root@c7-54-git ~]# yum install git-all`

`[root@c7-54-git ~]# yum install git`

`[root@c7-54-git ~]# yum install git-core`

`[root@c7-54-git ~]# git --version`

#### Config,

`[root@c7-54-git ~]# git config --global user.name "Anup Kumar Mondal"`  

`[root@c7-54-git ~]# git config --global user.email "bca.anup@gmail.com"`  

`[root@c7-54-git ~]# git config --list`

<br>
<br>

#### Source Installation

`[root@c7-54-git ~]# yum groupinstall "Development Tools"`

`[root@c7-54-git ~]# yum install gettext-devel openssl-devel perl-CPAN perl-devel zlib-devel`

`anup@u22-128-YT-MACHINE:~$ sudo apt-get install libz-dev libssl-dev libcurl4-gnutls-dev libexpat1-dev gettext cmake gcc`

`[root@c7-54-git ~]# wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.9.5.tar.gz`

`[root@c7-54-git ~]# tar -xvzf git-2.9.5.tar.gz`

`[root@c7-54-git ~]# cd git-2.9.5/`

`[root@c7-54-git git-2.9.5]# make configure`

`[root@c7-54-git git-2.9.5]# ./configure --prefix=/usr/local`

`[root@c7-54-git git-2.9.5]# make install`

`[root@c7-54-git git-2.9.5]# git --version`

`1git version 2.9.5 2`

#### Config,

`[root@c7-54-git ~]# git config --global user.name "Anup Kumar Mondal"`  

`[root@c7-54-git ~]# git config --global user.email "bca.anup@gmail.com"`  

`[root@c7-54-git ~]# git config --list`

<br>
<br>

### Ubuntu Installation,

`anup@megatron:~$ sudo apt-get update`

`anup@megatron:~$ sudo apt-get install git`

`anup@megatron:~$ git --version`

#### Config,

`anup@megatron:~$ git config --global user.name "Anup Kumar Mondal"`  

`anup@megatron:~$ git config --global user.email "bca.anup@gmail.com"`  

`anup@megatron:~$ git config --list`

<br>
<br>


### Windows Installation,

Download , [Git](https://git-scm.com/)

#### Access on Git Bash

`anup.mondal@DOLAP234 MINGW64 ~ $ git --version`

    `git version 2.29.2.windows.3`

#### Access on Git CMD

`C:\Users\anup.mondal>git --version`

    `git version 2.29.2.windows.3`

#### Access on Powershell

`PS C:\Users\anup.mondal> git --version`

    `git version 2.29.2.windows.3`

#### Config,

`PS C:\Users\anup.mondal> git config --global user.name "Anup Kumar Mondal"`  

`PS C:\Users\anup.mondal> git config --global user.email "bca.anup@gmail.com"`  

`PS C:\Users\anup.mondal> git config --list`
