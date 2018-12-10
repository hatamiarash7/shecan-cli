# Shecan CLI

The Shecan CLI is used to configure your DNS name server based on Shecan website from the command line.

For more about Shecan see https://shecan.ir/

## Installation

The following instructions will place the shecan executable in a
virtualenv under `shecan/bin/shecan`.

- Shecan **requires** `>= Python 3.6.1`

### pip

This installs the latest stable, released version.

```
$ python3.6 -m venv shecan
$ shecan/bin/pip install shecan
```
# Quickstart

* Run ``shecan update`` - it will get shecan dns nameservers and save them into database.
* Run ``shecan list`` it will show shecan dns name servers from the database.
* Run ``shecan set --id 1 --temporary`` It will configure your DNS temporarily by moving your current `/etc/resolv.conf` file and replace it with shecan DNS name server.
* Run ``shecan verify`` It will check your DNS name server and make sure that shecan works fine for you.