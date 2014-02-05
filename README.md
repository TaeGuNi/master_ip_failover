# master vip failover
This is virtual IP failover script for MHA.


## Overview

### Version
alpha 0.0.2

## Manual

### Usage

**app.cnf**
> *master_ip_failover_script*=/path/to/bin/master_ip_failover *--network_type*=eth0 *--gateway*=192.168.0.1 *--virtual_ip*=192.168.0.100 *--key*=0

### ssh authorized

1. use ssh-keygen
2. use sshpass command
> if you choice it.
> change line 122, 134, 136, 141

### Refer URL

> <https://code.google.com/p/mysql-master-ha/>
