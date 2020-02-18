# ans_join_realm
Ansible Role to Join a RHEL / CENTOS Machine to an AD Realm

This Requires that pexpect be installed on your image.
Also Requires Standard SSSD Packages (realmd, sssd, krb5-workstation, oddjob, oddjob-mkhomedir, etc)

Varibles required:
bind_user : Username with the ability to join domain
bind_password : Password for aforementioned username
serversn : Hostname of the machine

Modify the template to match your domain name.
