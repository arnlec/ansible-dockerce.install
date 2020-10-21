dockerce.install
=========

Install docker service on CentOS 7

Requirements
------------

No requirement

Role Variables
--------------

    - dockerce_repository:
        baserurl: https://download.docker.com/linux/centos/7/$basearch/stable
        gpgkey:  https://download.docker.com/linux/centos/gpg
    - dockerceVersion
    - dockerce_http_proxy

Dependencies
------------

No dependency

Example Playbook
----------------

    - hosts: servers
      roles:
         - dockerce.install
           dockerceVersion: 18.09

License
-------

BSD

Author Information
------------------

arnaud@lecann.com
