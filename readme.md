# swedef

swedef is a script that lets you find the definition, conjugation, and etymology of Swedish words.

The script relies on the dictionaries SAOL, SAOB, and SO, available from [svenska.se](https://svenska.se).


## Installation

```
git clone git@github.com:johan-andersson01/swedef.git
cd swedef
make install
```

### Uninstall
```
cd swedef
make uninstall
```

## Usage

```
usage: swedef [-h] [-d {saol,so,saob} [{saol,so,saob} ...]] words [words ...]

positional arguments:
  words                 Include one or more search queries

optional arguments:
  -h, --help            show this help message and exit
  -d {saol,so,saob} [{saol,so,saob} ...], --dicts {saol,so,saob} [{saol,so,saob} ...]
                        Select which dictionaries you want to use
```
