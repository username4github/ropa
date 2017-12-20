# ropa
![screenshot](https://github.com/orppra/ropa/raw/master/screenshots/ropa_screenshot.png)

[![Build Status](https://travis-ci.org/orppra/ropa.svg?branch=master)](https://travis-ci.org/orppra/ropa)

ropa is a [Ropper-based](https://github.com/sashs/Ropper) GUI that streamlines crafting [ROP](https://en.wikipedia.org/wiki/Return-oriented_programming) chains. It provides a cleaner, more user-friendly interface when using Ropper as compared to the command line. It can provide a smoother workflow for crafting the rop chain in the GUI, then exporting the final chain in the desired format. For those used to using CLI, this tool may serve as a cleaner interface to filter out the relevant gadgets.

Features include:
- Gadget searching with ropper
- Easy gadget selection
- Group multiple gadgets
- Export rop chain as binary file or python scripts (struct/pwntools/custom)
- Project saving

## Table of Contents
- [Install](#install)
- [Usage](#usage)

## Install
We use the [Ropper API](https://github.com/sashs/Ropper) for our gadget searching. The GUI runs on top of PyQt4.

```
# ropper
pip install Ropper

# pyqt4
sudo apt install python-qt4
sudo yum install PyQt4
```

## Usage
Run the following command to start ropa:
```
python ropa.py
```
