Role nginx
==========

Настройка web сервера nginx

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)


Example Playbook
----------------

    - hosts: servers
      roles:
         - role: nginx
           nginx_port: 8080

Test Role
---------

    molecule test

License
-------

BSD

Author Information
------------------

Sedov Andrey

e-mail: sedoy80@gmail.com
