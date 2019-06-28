mount-nfs
=========

Inspect NFS reachability and mount it

Requirements
------------

None.

Role Variables
--------------

Specify share address, share name and mount point:

    nfs_address: 192.168.0.x
    nfs_mountpoint: /mnt
    nfs_share: /my_share

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: hosts_group
      roles:
         - { role: mount-nfs, nfs_address: 192.168.0.x, nfs_mountpoint: /mnt, nfs_share: /my_share }

License
-------

MIT
