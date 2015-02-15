mapr_nfs
========

Install mapr-nfs.

Requirements
------------



Role Variables
--------------

```
proxy_env:
  http_proxy: http://1.2.3.4:3128
  https_proxy: http://1.2.3.4:3128
```

Dependencies
------------


Example Playbook
-------------------------

```
- hosts: nfs
  roles:
    - mapr_nfs
```

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com