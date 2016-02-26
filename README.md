Role Name
=========

This [Ansible](http://ansible.com/) role allows you to install and manage
the [rspamd](https://rspamd.com/) open-source spam filtering system server.

Dependencies
------------

- `debops.postfix`

Example Playbook
----------------

    - hosts: mail
      roles:
         - debops.postfix
         - rspamd 

License
-------

[GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

Author Information
------------------

`rspamd` role was written by:
- Emile Morel | [GitHub](https://github.com/bleuchtang)

