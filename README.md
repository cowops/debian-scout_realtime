Debian-ScoutRealtime
====================

Scout_realtime is top for the modern developer

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

ruby
ruby-dev
rubygems

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-scout_realtime }

Tasks
-----

  - Install [scout_realtime](http://scoutapp.github.io/scout_realtime/)

License
-------

BSD
