# Pip


The most crucial third-party Python software of all is Setuptools, which extends the packaging and installation facilities provided by the distutils in the standard library. Once you add Setuptools to your Python system you can download and install any compliant Python software product with a single command. It also enables you to add this network installation capability to your own Python software with very little work.

To obtain the latest version of Setuptools for Windows, run the python script available here: [**ez_setup.py**](https://bitbucket.org/pypa/setuptools/raw/bootstrap/ez_setup.py)

Just run the following in the folder where you saved the file.
```
> python ez_setup.py
```

You’ll now have a new command available to you: `easy_install`. It is considered by many to be deprecated, so we will install its replacement: `pip`. Pip allows for uninstallation of packages, and is actively maintained, unlike easy_install.

To install pip, run the python script available here: [**get-pip.py**](https://raw.github.com/pypa/pip/master/contrib/get-pip.py)
```
> python get-pip.py
```

- - -
Sourced From:
http://docs.python-guide.org/en/latest/starting/install/win/
