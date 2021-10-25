# napalm-cumulus

This is a [NAPALM](https://napalm.readthedocs.io/en/latest/) driver for cumulus linux through ssh.

This is an hard fork of https://github.com/mattlan/napalm-cumulus which has 2 original authors:
- mattlan
- Gabriele Gerbino

Hard fork was intentional because driver needed more update and last commits from orignal authors have 4-5 years.
This ensures that the repo will not be deleted by owners and can be updated

## Install

There is no PyPi repo has Orange didn't set up anything for now, to install use command line:

```shell
pip install git+https://github.com/orange-cloudfoundry/napalm-cumulus.git@<release version>
```

## Usage

you can use this new driver, example with napalm command line:

```
napalm --user myuser --vendor cumulus my-mellanox.switch.company.com call get_interfaces
```


