# HypotRucioPolicy
This is the Rucio policy package for the Hypot instance.

## How to use this policy package
* Make sure the directory containing the `HypotRucioPolicy` directory is in the `PYTHONPATH` for the Rucio server.
* Set `package = HypotRucioPolicy` in the `policy` section of the Rucio configuration file.

## Source files
* `__init__.py` - registers algorithms (currently none).
* `permission.py` - permission functions for the policy package.
* `schema.py` - schema functions and data for the policy package. Currently just a copy of the generic permissions without modifications.

## More Information
* https://rucio.cern.ch/documentation/operator/policy_packages
