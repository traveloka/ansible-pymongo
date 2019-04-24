# shared/pymongo #

Installs pymongo.

## Requirements ##

No special pre-requisites.

## Role Variables ##

### Defaults ###

    - name: pymongo_version 
      default: 3.3.0
      description: Version of pymongo to install

### Vars ###

None.

## Dependencies ##

Ensure pip is installed

## Example Playbook ##

    - hosts: servers
      roles:
         - role: pymongo
