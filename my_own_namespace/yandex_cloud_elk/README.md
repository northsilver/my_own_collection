# Ansible Collection - my_own_namespace.yandex_cloud_elk

Collection for LAB.

Include [module](https://github.com/northsilver/my_own_collection/blob/master/my_own_namespace/yandex_cloud_elk/plugins/modules/my_own_module.py)

Role Variables
--------------

|Name|Description|
|-----|-----|
| path | define path for file
| content | define text in file

Example Playbook
----------------

[Collection](https://github.com/northsilver/my_own_collection/blob/1.0.0/single_role_collection.yml)

        - name: Test my_own_module
          hosts: localhost
          roles:
            - role: netology.yandex_cloud_elk.my_own_module

License
-------

MIT

Author Information
------------------

Created by [Ivan Shumbasov](https://github.com/northsilver)

