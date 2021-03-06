# ofxstatement-be-ing 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
# ING Belgium plugin for ofxstatement 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This project provides a custom plugin for [ofxstatement](https://github.com/kedder/ofxstatement) for ING (BE). It is based
on the work done by TheoMarescaux (https://github.com/TheoMarescaux/ofxstatement-be-ing)
and corrected for INGs latest changes to the csv files generated by their homebanking.

`ofxstatement`_ is a tool to convert proprietary bank statement to OFX format,
suitable for importing to GnuCash. Plugin for ofxstatement parses a
particular proprietary bank statement format and produces common data
structure, that is then formatted into an OFX file.

Users of ofxstatement have developed several plugins for their banks. They are
listed on main [`ofxstatement`](https://github.com/kedder/ofxstatement) site. If your bank is missing, you can develop
your own plugin.

## Installation

### From PyPI repositories
```
pip3 install ofxstatement-be-ing
```

### From source
```
git clone https://github.com/jbbandos/ofxstatement-be-ing.git
python3 setup.py install
```

## Usage
```
$ ofxstatement convert -t ingbe input.csv output.ofx
```
