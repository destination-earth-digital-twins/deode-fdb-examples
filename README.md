# fdb examples
Python and Jupyter notebook examples for fdb usage in DE330

## Install

To install the required environment e.g. locally do, in this case with micromamba, and preferred python version

```
micromamba create -n deode_fdb_examples python=3.12
micromamba env update -n deode_fdb_examples -f environment.yml
```

## Activate
```
micromamba activate deode_fdb_examples
module load ecmwf-toolbox/2025.10.1.0
```

## List available georefs from FDB for a specific date

```
python3 ./find_georef.py
```

# Create a kernel for jupyer notebook if of interest

```
python3 -m ipykernel install --user --name=deode_fdb_examples
```
