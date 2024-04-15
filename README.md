Role Name
=========
node-exporter

Requirements
------------
null

Role Variables
--------------
port: 9100

Dependencies
------------
二进制部署，Systemd创建启动服务。

Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }



