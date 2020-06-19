zfs-rescue
=========

This ansible playbook sets up a working Debian installation with ZFS-on-root. It's only tested on Hetzner servers.

Requirements
------------
- Hetzner root server
- Rescue mode

Role Variables
--------------
These variables need to be defined prior to executing this playbook.
```cat defaults/main.yml
osrelease: buster
osreleasebp: buster-backports
drive1: nvme0n1
drive2: nvme1n1
diskbyid1: nvme-KXG60ZNV512G_TOSHIBA_106S10CJT9LM
diskbyid2: nvme-KXG60ZNV512G_TOSHIBA_106S10COT9LM
root_password: 
ip_address: 
gateway: 
```


License
-------

BSD
