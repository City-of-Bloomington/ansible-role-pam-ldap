pam-ldap
=========

Configures PAM Ldap authentication


Role Variables
--------------

```yml
pam_ldap:
  uri:            "ldaps://example.org:636"
  base:           "OU=Departments,DC=example,DC=org"
  binddn:         "admin@example.org"
  bindpw:         "secret password"
  login_attribue: "sAMAccountName"
```

Dependencies
------------

* [City-of-Bloomington.linux](https://github.com/City-of-Bloomington/ansible-role-pam-ldap)

Copying and License
-------

This material is copyright 2023 City of Bloomington, Indiana
It is open and licensed under the GNU General Public License (GPL) v3.0 whose full text may be found at:
https://www.gnu.org/licenses/gpl.txt
