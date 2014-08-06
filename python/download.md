# Download

Go to the [**Python Download Page**](https://www.python.org/downloads/windows/) and download the latest version of Python 2.7.

The Windows version is provided as an MSI package. To install it manually, just double-click the file. The MSI package format allows Windows administrators to automate installation with their standard tools.

### PATH

By design, Python installs to a directory with the version number embedded, e.g. Python version 2.7 will install at `C:Python27`, so that you can have multiple versions of Python on the same system without conflicts. Of course, only one interpreter can be the default application for Python file types. It also does not automatically modify the `:envvar:`PATH environment variable, so that you always have control over which copy of Python is run.

Typing the full path name for a Python interpreter each time quickly gets tedious, so add the directories for your default Python version to the **PATH**. Assuming that your Python installation is in `C:Python27`, add this to your `:envvar:`PATH:

```
C:\Python27\;C:\Python27\Scripts\
```

You can do that by running the following in `powershell`.
```
[Environment]::SetEnvironmentVariable("Path", "$env:Path;C:\Python27\;C:\Python27\Scripts\", "User")
```

- - -
Sourced From: http://docs.python-guide.org/en/latest/starting/install/win/
