psplibraries
============

[![Build Status](https://travis-ci.org/nabilbendafi/ansible-role-psptoolchain.png?branch=master)](https://travis-ci.org/nabilbendafi/ansible-role-psptoolchain)

This role installs and configures the open-source [psplibraries](https://github.com/pspdev/psplibraries) for PSP homebrew development.

Installation
------------

```
$ ansible-galaxy install nabilbendafi.ansible-role-psplibraries 
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

[nabilbendafi.psptoolchain](https://github.com/nabilbendafi/psptoolchain)

License
-------

[MIT](LICENSE.txt)

Author Information
------------------

[Nabil Bendafi](https://github.com/nabilbendafi)
