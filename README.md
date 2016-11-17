# ansible-aegir

This script installs all required RPMs to run aegir

It will ask for the FQDN and the password you want to use for the mariaDB admin account.

To install, switch to root and run
```
yum -y install git;git clone https://github.com/avenging/ansible-aegir.git;cd ansible-aegir;./run.sh
```

When upgrading ansible, you must upgrade drush yourself. This script uses drush to install aegir, so aegir cant upgrade it.
