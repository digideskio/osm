# osm - Open Source Mail

The intent behind `osm` (pronounced like `awesome`) is to provide people with a simple way to set up and manage their own email server infrastructure, osm consist on an [ansible](http://www.ansible.com/home) recipies that will any vps from zero to ready-to-go email server.

Osm is by no means production ready at this point, it's a very early-stages ongoing effort. We are **extremely** open to contributions!

## Community

Want to discuss ideas? We hang out in the [`#open-source-mail`](http://webchat.freenode.net/?channels=#open-source-mail) IRC channel in [freenode](https://freenode.net/). :)

## How to use it

```bash
$ cp .inventory.sample .inventory
$ # Edit your .inventory file, adding the IP to your VPS, osm will initially work on Debian and related distros.
$ ansible-playbook -i .inventory provision.yml 
```
