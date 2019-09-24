cloud3rsio.common_packages
=========

Install common packages.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.common_packages
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `common_packages` | Reference to [defaults/main.yml](defaults/main.yml) | List |

Dependencies
------------

- `cloud3rsio.yumrepo_epel`

Example Playbook
----------------

```
- hosts: all
  roles:
    - role: cloud3rsio.common_packages
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
