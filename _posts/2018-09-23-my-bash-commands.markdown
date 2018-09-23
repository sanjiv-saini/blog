---
layout: post
title:  "Linux learning points"
date:   2018-09-23 22:22:44 +0530
categories: bash
---

* ls
* alias name='command'
* wc -l
* chmod 700 fileName
* chown ownername:grpname filename
* chgrp grpname filename
* PATH=$PATH:<YOUR OWN PATH>
* $PS1='COMMAND PROMPT DISPLAY'
* /bin: contains executable binaries
* /sbin: contains executable binaries for root users
* /root: root user home directory
* /lib: contains library used by exec binaries
* /home/username: users home directory, also refered by ~
* /etc: contains configuration files
* /var: contains variable files, which changes, like log files
* modify .bashrc file in linux for some configuration for bash to be available in all session
* modify .bash_profile in windows or mac
* vi: use caps G, to go to end of file, <no.>+ G
* vi: <no.>+w, to move that no. of words forward
* vi: set number, to show lines
* vi: set showmode, to show current mode in vi
* scp filename removeUser@remoteIP:pathThere
* SSH port: 22, FTP: 21 for control, 20 for data.
* adduser username
* passwd, to change password
* /etc/sudoers, file to update superuser previliges