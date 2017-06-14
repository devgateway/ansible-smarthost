# smarthost

Set up mail relaying to a smarthost.

Role Variables
--------------

### smhs\_relay\_host

FQDN of the smarthost. Also used to skip running this role on smarthost itself.

### smhs\_main\_cf

Path to Postfix `main.cf` file. Defaults to `/etc/postfix/main.cf`.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: smarthost
           smhs_relay_host: mx.example.org

License
-------

GPLv3+

Author Information
------------------

Development Gateway
