Shorewall
=========

This is to install shorewall on a Archlinux system

Requirements
------------

There are no additional requirements for this role, beyond the requirements for
Ansible and installing packagaes with Archliux's `pacman`

Role Variables
--------------

There are currently no additional variables for this role.

Dependencies
------------

There are no additional role dependancies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: shorewall }


Development
===========

This role uses [Molecule](http://molecule.readthedocs.io/) as a testing and
development framework, which has other requirements. If you wish to contribute,
please ses [CONTRIBUTING](CONTRIBUTING.md).

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a
website (HTML is not allowed).
