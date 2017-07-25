hxpro.docker-engine
===================

Install docker-engine on CentOS from official docker repository

Dependencies
------------

 - hxpro.bootstrap

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: hxpro.docker-engine
           docker_hosts:
             - 'unix:///var/run/docker.sock'
             - "tcp://0.0.0.0:2375"


License
-------

WTFPL

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
