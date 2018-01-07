[![Build Status](https://travis-ci.org/wtanaka/ansible-role-screen.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-screen)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-screen.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-screen)

wtanaka.screen
==============

Installs GNU screen

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.screen

### `screen_should_shortcircuit`

Default: True

when True, the role short-circuits itself if screen is already installed

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)


License
-------

GPLv2

Author Information
------------------

https://wtanaka.com/
