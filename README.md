Role Name
=========

This role is a part of Parity Challenge!

Requirements
------------

* Ansible
* Docker
* AWS Credentials
* Virtual Machina with ssh


Example Playbook
----------------

This credentials are just a sample, you need to create your own on AWS dashboard!

    - hosts: servers
      vars:
        AWS_ACCESS_KEY: AKIAJ2PLJZWIL3ZJ2OKQ
        AWS_SECRET_KEY: QWuu+eJLY6cbatqOthYKR+AM3y5YVe/MUprW1+1y
      roles:
        - igordcsouza.parity

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
