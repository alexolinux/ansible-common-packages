ansible-common-packages
=========

Role for Amazon Linux 2 AMI - Package Installation and a few additional things.

Requirements
------------

Node servers must be AMI Amazon Linux 2.

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

BSD

Author Information
------------------

Alex Mendes

https://www.linkedin.com/in/mendesalex/
