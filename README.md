keydist-utility
===============

CVL desktop utility for distributing SSH keys, also know as the CVL's Remote File Manager.

The CVL's Remote File Manager can be found in the panel at the top of the CVL Desktop:

![Image](https://raw.github.com/CVL-dev/keydist-utility/master/images/CVL%20Remote%20File%20Manager.png?raw=true)

To add a new SSHFS mount point to the CVL Desktop, click the "Add Host" button:

![Image](https://raw.github.com/CVL-dev/keydist-utility/master/images/CVL%20Remote%20File%20Manager%20SSHFS%20mounting%20MyTardis.png?raw=true)

The remote file system can be configured to use the CVL's LDAP directory for authentication:

![Image](https://raw.github.com/CVL-dev/keydist-utility/master/images/CVL%20Remote%20File%20Manager%20LDAP%20authentication%20for%20MyTardis%20SSHFS%20mount.png?raw=true)

Mounted file systems are listed below:

![Image](https://raw.github.com/CVL-dev/keydist-utility/master/images/CVL%20Remote%20File%20Manager%20Mounted.png?raw=true)

User cvluser1's MyTardis data is now available as a filesystem.  This user has one MyTardis experiment (experiment ID 119) and one data set within that experiment (data set ID 252). Mounted file systems can be browsed in Nautilus (or any other file browser):

![Image](https://raw.github.com/CVL-dev/keydist-utility/master/images/MyTardis%20SSHFS%20mount%20on%20CVL%20Desktop.png?raw=true)
