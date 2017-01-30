# ansible-ensure-python

Ensure that Python 2 is installed using only `raw` commands. This is useful when you need to deploy
on Ubuntu 16.04 hosts where python2 is not installed by default.

When you call this, make sure that your playbook sets `gather_facts: no` if you don't want it to
fail.

## Requirements

* One of the supported targets:
  * Ubuntu 16.04
  * Ubuntu 14.04
