# CENTOS 6.6 README.md

## Material for CENTOS 6.6 Configuration

A CentOS 6.6 operating systemis the basis for basic server management activities.

The manual system configurations are reworked into executable configuration
management formats.  These formats are based on the use of Vagrant.

The Shell directory contains a bash shell script provider that is used by
Vagrant to configure the CentOS 6.6 server. Configuration goals are:
1. Create two new users.
2. Use ssh keys for authencation.
3. Disable root ssh log in.
4. Disable Vagrant user

The Ansible directory contains an Ansible yml script provider that is used by
Vagrant to configure the CentOS 6.6 server
