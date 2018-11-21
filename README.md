# STATA-Python-Ipystata-
Enabling the use of Stata together with Python via Jupyter (IPython) notebook through the Ipystata package.
# STATA Tutorial(enabled by Ipystata)
STATA tutorial using notebook STATA cell magic.
# STATA Magic
STATA using cell magic

```
%%Stata
(Your STATA statement)
```

## Jupyterlab STATA tutorial

This project is a tutorial on STATA using STATA cell magic in Jupyterlab notebooks

The tutorial taken through is this [book](https://www.stata.com/bookstore/data-analysis-using-stata/) by Ulrich Kohler and Frauke Kreuter:

## Getting Started

### Prerequisites

Be running Jupyter. I use the anaconda installer: https://www.continuum.io/downloads

You'll also need to install the library and dependencies listed below, if you don't have it

```
ipystata
```

### **You can install IPyStata 0.3.0 using:**

    pip install ipystata
### **You can update a previous installation to 0.3.0 using:**

    pip install ipystata --upgrade --force-reinstall
### Dependencies
Python 2.7 or 3.x  
IPython 3 or 4 (http://ipython.org/)  
Pandas 0.17.x + (http://pandas.pydata.org/) (I recommend to use a distribution like Anaconda)  
Recent version of Stata (13 / 14 preferably) (http://www.stata.com/)  

### Set up IPyStata

#### Modes of operation:
IPyStata can communicate with Stata using two different techniques:  

1. Stata Automation, works on --> Windows
2. Stata Batch mode, works on --> Windows, Mac OS X, and Linux

The `Stata Automation` mode has a richer feature set compared to the `Stata Batch mode`.  
Unfortunately, Stata only supports `Stata Automation` for Stata instances running on a Windows OS.

For Windows `Stata Automation` is set as default but it is possible to set it to use `Stata Batch mode` instead.  
For Unix operating systems (OS X and Linux) it is only possible to use IPyStata in `Stata Batch mode`.

### Windows setup (Stata Automation)

#### Register your Stata instance:
1. Go to your Stata installation directory and either:

    -  Shift + Right-Click --> click "Open command window here"  
       or
    - Open command window (search for "cmd") and type:  
       `cd C:\Program Files (x86)\Stata14`      (Obviously change it to your Stata directory)  

2. Look up the name of your Stata executable (e.g. `StataMP-64.exe`) and in your command window type:  
`StataMP-64.exe /Register`

You can also follow instructions at:https://github.com/TiesdeKok/ipystata#get-ipystata

You can find examples like
1. http://nbviewer.jupyter.org/github/TiesdeKok/ipystata/blob/master/ipystata/Example.ipynb

## To use Ipystata
IPyStata is imported and loaded using `import ipystata`.
A cell with Stata code is defined by the cell magic `%%stata`.

## Author

* **Peter Otieno** - [peterakworo](https://github.com/peter-akworo) - [LinkedIn](https://www.linkedin.com/in/peter-onyango-184446132/)

## Acknowledgments

* To Vincent Were my STATA mentor.

