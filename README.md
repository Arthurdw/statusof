# Statusof

Small python script to check the status of a list of urls.

# Parameters:

- `-u`, `--url`: **url to check**
- `-f`, `--file`: **file containing urls to check**
- `-t`, `--timeout`: **timeout in seconds**
- `-s`, `--secure`: **Try to use HTTPS instead of HTTP**
- `-h`, `--help`: **show this help message**

# Usage:

## Single url

- `statusof.py -u example.com`
- `statusof.py -u example.com -t 10`

## Multiple urls

- `statusof.py -f urls.txt`
- `statusof.py -u example.com -u example2.com`

# Installation

Statusof can be installed with pip:

```
pip install -U statusof
```
