## Building Locally

### Prerequisites

The following are assumed:
* Python 3.11.4 or similar compatible version
* MacOS 13.2 (Ventura)

This book was built with [Jupyter Books][1]. Do give it a read before starting off.

### Setup `virtualenv` (one-time)

```
pip install virtualenv
python -m virtualenv ./env
source env/bin/activate
pip install -r requirements.txt
```

### Activate `virtualenv` and build the book 

Each time you open a terminal, activate the `virtualenv` using
```
source env/bin/activate
```

Then build the book 

```
jupyter-book build troubleshooting_handbook/
```

[1]: https://jupyterbook.org/
