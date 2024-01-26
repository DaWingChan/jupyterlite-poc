# JupyterLite with lab extension POC

## Preparation

---
- Python 3.9+
- nodejs 18+

## Requirements
```shell
    python -m pip install -r requiremenets.txt -i https://pypi.tuna.tsinghua.edu.cn/simple 
```

## JupyterLite
Here is the part of Jupyterlite setup with a standalone server
### Initialize
```shell
    jupyter lite init --output-dir dist
```
### Build Packages
```shell
    jupyter lite build --output-dir dist
```

