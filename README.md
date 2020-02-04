oVirt Create vNIC Profiles 
=========

Create vnic profiles in oVirt

Requirements
------------


Role Variables
--------------

vnic_profiles: List of vnics to be added
* name: Name of vnic profile
* network: Name of network profile should be associated with
* datacenter: Name of data center that profile should be apart of

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: ovirthost
      roles:
         - { role: ovirt_create_vnic_profiles }

License
-------

BSD

Author Information
------------------

Marc Colburn Red Hat
