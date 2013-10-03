# puppet-server-bootstrap

Shell script to bootstrap puppet server on a minimal Red Hat/CentOS/Fedora install

## Instructions

1. Do a minimal install of your preferred OS (see supported flavours below)
2. Grab the psb script and run it:

```
curl -L https://raw.github.com/robinbowes/puppet-server-bootstrap/master/psb -o psb
bash psb
```

## Supported OSes

The script currently supports:
* CentOS/Red Hat/Amazon Linux 5/6
* Fedora 17/18/19

Others can easily be added if there exists for that repo:
* a puppetlabs repo
* an epel repo

Robin Bowes <robin.bowes@yo61.com>
