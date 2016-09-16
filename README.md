psplibraries
============

[![Build Status](https://travis-ci.org/nabilbendafi/ansible-role-psplibraries.png?branch=master)](https://travis-ci.org/nabilbendafi/ansible-role-psplibraries)

This role installs and configures the open-source [psplibraries](https://github.com/pspdev/psplibraries) for PSP homebrew development.

Installation
------------

```
$ ansible-galaxy install nabilbendafi.psplibraries
```

```
# psplibraries.yml
- hosts: localhost
  roles:
    - nabilbendafi.psplibraries
```

```
$ ansible-playbook psplibraries.yml
```

Dependencies
------------

[nabilbendafi.psptoolchain](https://github.com/nabilbendafi/ansible-role-psptoolchain)
[nabilbendafi.psp-ports](https://github.com/nabilbendafi/ansible-role-psp-ports)

License
-------

[MIT](LICENSE.txt)

Author Information
------------------

[Nabil Bendafi](https://github.com/nabilbendafi)
