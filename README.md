Ansible Role - Composer
=========================

A composer role for elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Variables
--------------

    elao_composer_config_auth:    # Auth config
      github-oauth:
        github.com: xxxx


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.composer }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
