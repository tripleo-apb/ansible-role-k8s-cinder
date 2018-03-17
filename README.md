Role Name
=========

Ansible Role to Deploy OpenStack Cinder in OpenShift/Kubernetes.

Requirements
------------

Ansible Kubernetes Modules. MariaDB and RabbitMQ at the least. Keystone if authentication is required.

Role Variables
--------------

Dependencies
------------

MariaDB and RabbitMQ at the least. Keystone if authentication is required.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPL v3

Author Information
------------------

Kiran Thyagaraja
kthyagaraja@gmail.com
