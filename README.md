Ansible Role: Polaris
=========

Install Lastest Synopsys Polaris CLI

Official installation [documentation](https://sig-docs.synopsys.com/polaris/topics/t_installing-cli.html)

Role Variables
--------------

Polaris CLI download base URL: 

* for example, if your organization is `myorg`, `myorg` variable will be: https://myorg.polaris.synopsys.com

Polaris variables in `polaris/defaults/main.yml`


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

This role was created in 2021 by Xianpeng Shen.
