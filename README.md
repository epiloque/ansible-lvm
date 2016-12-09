<p align="right">
    <a href="https://travis-ci.org/epiloque/ansible-lvm">
        <img src="https://travis-ci.org/epiloque/ansible-lvm.svg?branch=master"
             alt="build status">
    </a>
        <a href="https://galaxy.ansible.com/epiloque/lvm">
        <img src="https://img.shields.io/badge/ansible--galaxy-lvm-blue.svg"
             alt="ansible galaxy">
    </a>
</p>

lvm role

* installs required software and tools
* enables lvmetad daemon
* creates lvm volume group and adds provided block device to it as physical volume
* reigsers volume group name fact

## Role Variables

Available variables are listed below:

```yaml
lvm_volume_group_name: default
lvm_physical_device: /dev/xvdh
```

## License

This software is released under the terms of the BSD-3-Clause license.

This software includes or is derivative of works distributed under the licenses
listed below. Please refer to the specific files and/or packages for more
detailed information about the authors, copyright notices, and licenses.

* [mantl](https://github.com/mantl/mantl) Copyright © 2015 Cisco Systems, Inc.
