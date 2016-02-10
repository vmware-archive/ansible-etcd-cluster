etcd-cluster
============

Setup an etcd cluster spanning all hosts in the current play.

Current version: 0.1.0

Role Variables
--------------

- etcd_service: the service unit to start
- etcd_dropin_dir: where to drop the service drop-in (systemd is assumed)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - sigma.coreos-bootstrap
         - sigma.etcd-cluster

License
-------

MIT
