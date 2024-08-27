Role Name
=========

Set ACL on the given directory (consider merging with `mkdir` role).

Requirements
------------

`acl` package should be installed on the target system.

Role Variables
--------------

`directory`: path to the directory that ACL will be set on.

Dependencies
------------

None

Example Playbook
----------------

```yaml
roles:
  - role: acl_directory
-   directory: /path/to/my/dir
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).