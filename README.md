WARNING: This role is no longer maintained !!!
==============================================

You are strongly encouraged to switch to the new roles stack on https://github.com/ElaoInfra
--------------------------------------------------------------------------------------------

By the way, this role will remain available on https://github.com/ElaoLegacy
----------------------------------------------------------------------------


Ansible Role - Composer
=========================

A composer role for elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Dependencies
------------

This role requires php cli binary.

Role Variables
--------------

    elao_composer_config_auth:    # Auth config
      github-oauth:
        github.com: xxxx


Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: elao.php }
        - { role: elao.composer }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
