Ansible deploy-npm-install
==========================

Installs node modules on release dir. It has two different strategies.
If node_modules are committed to repository it just runs `npm rebuild`.
If not, then it just installs node_nodules. Currently there is some bug
in `npm install`. It does not allow to create symlink to shared bundle dir.
Maybe I'll fix it in future.

For more information about deployment setup see this [overview](https://github.com/kunik/ansible-role-deploy-metadata/blob/master/USAGE.md)

Requirements
------------

No

Role Variables
--------------

No

Dependencies
------------

No

License
-------

BSD
