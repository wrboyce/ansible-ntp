ntp
===

[![Build Status](https://travis-ci.org/wrboyce/ansible-ntp.png)](https://travis-ci.org/wrboyce/ansible-ntp)

Configure NTP client on Debian/Ubuntu based systems.

Role Variables
--------------

`ntp_servers` should be set to an array of upstream ntp servers.

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: wrboyce.ntp
          ntp_servers:
            - 0.uk.pool.ntp.org
            - 1.uk.pool.ntp.org
            - 2.uk.pool.ntp.org
            - 3.uk.pool.ntp.org

License
-------

BSD

Author Information
------------------

* Will Boyce
