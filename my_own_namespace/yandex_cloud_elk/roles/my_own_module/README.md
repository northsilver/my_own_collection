MY-OWN-MODULE
=========

Lab [module](https://github.com/northsilver/my_own_collection/blob/master/my_own_namespace/yandex_cloud_elk/plugins/modules/my_own_module.py)

Requirements
------------

- venv was used to create the environment

`python3 -m venv venv`

Role Variables
--------------

|Name|Description|
|-----|-----|
| path | define path for file
| content | define text in file

Dependencies
------------

Before run:

- create environment `. venv/bin/activate`
- setup dependencies `pip install -r requirements.txt`
- setup environment `. hacking/env-setup`


Example Playbook
----------------

Exapmle:
```bash
- name: Test my_own_module
  hosts: localhost
  roles:
    - role: my_own_namespace.yandex_cloud_elk.my_own_module
```

License
-------

MIT

Author Information
------------------
Created by [Ivan Shumbasov](https://github.com/northsilver)