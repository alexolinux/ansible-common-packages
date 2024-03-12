ansible-common-packages
=========

This Role provides follow resources:

- Custom /etc/hosts deployment.
- Enable/Install EPEL Repository.
- Installing list of packages from a list. 

Requirements
------------

For now this role provides package automations for RHEL only (Including Amazon Linux 2).

Role Variables
--------------

- <u>**packages:**</u>     It provides the package list you wish install on your servers.
- <u>**user:**</u>         sudo remote user.
- <u>**epel_install:**</u> Amazon Linux command to install epel repo.
- <u>**epel_enable:**</u>  Amazon Linux command to enable epel.

Dependencies
------------

There are no dependencies for this role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: aws
  roles:
    - ansible-common-packages
```

License
-------

GPL-3.0 license

Author Information
------------------

Alex Mendes

https://www.linkedin.com/in/mendesalex/
