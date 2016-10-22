Role Name
=========

Installation of tools than any self-respecting JavaScript developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* javascript_webstorm_install: true
* javascript_webstorm_version: 2016.2.4
* javascript_webstorm_build: 162.2228.20

* javascript_node_install: true
* javascript_node_version: v4.6.1

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.javascript-developer, javascript_node_version: v4.6.1 }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
