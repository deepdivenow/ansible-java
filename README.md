Java
=========

Install java

Role Variables
--------------

java_version
java_type - Type of java distribution

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansible-java
      vars:
         - java_version: 1.8.0
         - java_type: openjdk

License
-------

Apache

Author Information
------------------

Andrey Kislyak