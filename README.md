Vector role
=========

Роль для установки vector.

Requirements
------------

- ansible==9.3.0
- ansible-base==2.10.8
- ansible-core==2.16.4

Variables
--------------

Все перезаписываемые переменные в defaults/main.yml
| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
|clickhouse_ip: | 192.168.56.11 | - ip адрес БД, куда будут отсылаться метрики и логи|

Example Playbook
----------------

Добавить в playbook:

    - hosts: servers
      roles:
         - { role: vector-role }

License
-------

BSD

Author Information
------------------


