# Ansible MongoDB
Install MongoDB on Centos/Red Hat

## Installation
Clone this repository inside your ```roles``` directory

## Usage
There must be an ```app``` var with ```mongodb``` inside it defined as follows:

```
vars:
  app:
      mongodb:
        dbpath: /var/lib/mongo
````

> you may also specify ```app:``` in a separate YAML file and include it in ```vars_files```