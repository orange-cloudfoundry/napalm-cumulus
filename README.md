# napalm-cumulus

This is a [NAPALM](https://napalm.readthedocs.io/en/latest/) driver for cumulus linux through ssh.

This is a fork of <https://github/orange-cloudfoundry/napalm-cumulus/> which was a hard fork of <https://github.com/mattlan/napalm-cumulus/> which has 2 original authors:

- mattlan
- Gabriele Gerbino

Hard fork was intentional because driver needed more update and last commits from orignal authors have 4-5 years.
This new fork include Netmiko >4 support, and added NVUE support for Cumulus 5.

## Install

There is no PyPi repo, to install use command line:

```shell
pip install git+https://github.com/justinbrink/napalm-cumulus.git@<release version>
```

## Usage

you can use this new driver, example with napalm command line:

```shell
napalm --user myuser --vendor cumulus my-mellanox.switch.company.com call get_interfaces
```
