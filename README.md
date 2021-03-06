Ansible Role: Polaris
=========

Installs and configures Synopsys Polaris CLI

![Ansible Role](https://img.shields.io/ansible/role/55765)

Official installation [documentation](https://sig-docs.synopsys.com/polaris/topics/t_installing-cli.html)

Role Variables
--------------

Polaris CLI download base URL: 

* for example, if your organization is `myorg`, `myorg` variable will be: https://myorg.polaris.synopsys.com

Polaris variables in `defaults/main.yml`

Example Playbook
----------------

How to play polaris role:

    - hosts: servers
      roles:
         - { role: polaris, myorg: "https://myorg.polaris.synopsys.com"}

License
-------

MIT

Author Information
------------------

This role was created in 2021 by [Xianpeng Shen](https://shenxianpeng.github.io/).
