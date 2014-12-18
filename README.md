Ansible Role - Php 5.2
======================

A php 5.2 role for elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Handlers
-------------

    php restart  # Restart php service


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.php-5_2 }


License
-------

MIT

Author Information
------------------

http://www.elao.com/
