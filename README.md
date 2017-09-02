# Ansible-Amahi
Lets you setup an Amahi Server with Ansible.

Pseudocode:
1) gather code
2) verify access to intended server
3) make the following happen...
```
 rpm -Uvh http://f25.amahi.org/noarch/hda-release-10.0.0-1.noarch.rpm
 dnf -y install hda-ctl
 hda-install YOUR-INSTALL-CODE
```
4) install some other handy tools
5) run dnf/yum update
6) reboot
