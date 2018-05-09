Module documentation
====================

#.. automodule:: sf_user_account

#.. autoclass::  SolidFireUserAccount
    members: get_user_account_by_id, create_cluster_user, create_ldap_user, update_account, delete_account, apply
    
Synopsis
--------
    Creates, updates, and deletes HBAs in existing partitions of a CPC.
    The targeted CPC must be in the Dynamic Partition Manager (DPM) operational mode.

Requirements (on host that executes module)
-------------------------------------------
        Network access to HMC
        zhmcclient >=0.14.0
        ansible >=2.2.0.0




