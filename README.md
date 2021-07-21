This Project has been forked from https://github.com/Schlabonski/cubini, updated and customized for Windows PCs.
# cubini
A python library to control several Thorlabs' KPZ101 piezo controler cubes. Each KPZ101 is interfaced using the virtual com port [implementation](https://github.com/pyusb/pyusb/blob/master/tools/vcp_terminal.py) of `pyusb`.

## Installation
To install the package from source simply do
```
git clone https://github.com/Schlabonski/cubini
cd cubini
python3 setup.py install
```

*Requirements*: This library works on top of `pyusb` which uses `libusb` so these should both be installed as well.
