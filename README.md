# Ansible MongoDB
Install MongoDB on Centos/Red Hat/Fedora

## Installation
- Clone this repository inside your ```roles``` directory
or add as submodule: `git submodule add git@github.com:Vinelab/ansible-mongodb roles/mongodb`

- In your playbook:

```yaml
roles:
  - mongodb
```

## Usage

```yaml
vars:

  mongodb:
    dbpath: /var/lib/mongo
````
