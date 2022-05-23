# Statusof

Small python script to check the status of a list of urls.

## Parameters:

- `-u`, `--url`: **url to check**
- `-f`, `--file`: **file containing urls to check**
- `-t`, `--timeout`: **timeout in seconds**
- `-p`, `--precision`: **precision of the time**

## Flags

- `-s`, `--secure`: **Try to use HTTPS instead of HTTP**
- -`c`, `--colors`: **disable color output**
- `-h`, `--help`: **show this help message**

## Usage:

### Single url

- `statusof.py -u example.com`
- `statusof.py -u example.com -t 10`

### Multiple urls

- `statusof.py -f urls.txt`
- `statusof.py -u example.com -u example2.com`

## Installation

Statusof can be installed with pip:

```
pip install -U statusof
```

## Example preview

![image](https://user-images.githubusercontent.com/38541241/169846012-83a10495-78e9-4c42-82b0-49e8cb7d80e4.png)
