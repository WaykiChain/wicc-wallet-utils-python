## wicc_wallet_utils-python
WaykiChain Wallet Utility Library for raw transaction generation and signing and BaaS Posting etc operations

Written in Python

## Install via Pip
```
pip3 install wicc_wallet_utils==1.0.2
```

## Usage Reference
https://pypi.org/project/wicc_wallet_utils/1.0.2/

## Project Packaging Guide
https://packaging.python.org/tutorials/packaging-projects/

## pipy upload procedures
1. generate/update dist files

```
python3 setup.py sdist bdist_wheel
```

2. upload dist to pypi repo

```
python3 -m twine upload dist/*
```
