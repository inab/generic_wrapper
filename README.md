# Generic Wrapper

This generic wrapper is written for Python 3.6 and later.

* In order to install the dependencies you need `pip` and `venv` modules.
	- `pip` is available in many Linux distributions (Ubuntu packages `python3-pip`, CentOS EPEL package `python-pip`), 
	and also as [pip](https://pip.pypa.io/en/stable/) Python package.
	- `venv` is also available in many Linux distributions (Ubuntu package `python3-venv`). In some of them is 
	integrated into the Python 3.5 (or later) installation.

* The creation of a virtual environment where to install WES backend dependencies is done running:
  
```bash
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip wheel
pip install -r requirements.txt
```