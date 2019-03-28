Simple Ansible skeleton that provides a role with a tag.

### Overview

~~~
.
├── ansible.cfg
├── galaxy
│   └── rc-local
│       └── tasks
│           ├── main.yml
│           └── symon.yml
├── inventory
│   └── hosts
└── setup.yml
~~~

### Usage

```ansible-playbook --tags symon --limit pvdevmongo02 setup.yml```
