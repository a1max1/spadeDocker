spadeDocker
===========

An Ansible role that installs apache and is tested through Travis
on multiple platforms using Docker
This is only built as a sample for glaxy/travis/docker integration 

[![Build Status](https://travis-ci.org/a1max1/spadeDocker.svg?branch=master)](https://travis-ci.org/a1max1/spadeDocker)

Requirements
------------

running apt-get vs yum

Role Variables
--------------

located in defaults/main.yml

Example Playbook
----------------

example of how to use the role
  - hosts: servers
    roles:
      - { role: a1max1.spadeDocker, x: 42 }

Author Information
------------------
Ace of Spade

