Mongo replica set [![Build Status](https://travis-ci.org/SimpliField/ansible-mongo-replica-set.svg?branch=master)](https://travis-ci.org/SimpliField/ansible-mongo-replica-set)
=========

Setup mongo replica set

Requirements
------------

Need ansible 2+ and mongodb

Dependencies
------------

This module need pymongo

Example Playbook
----------------

```yaml
- hosts: mongo
  tasks:
  # init a replica set
  - mongodb_replica_set: state=initiated
```

License
-------

BSD
