# Virtualenv

After Setuptools & Pip are installed, the next development tool that you should install is [virtualenv](http://pypi.python.org/pypi/virtualenv/).

Use pip to do so.

```
> pip install virtualenv
```

The virtualenv kit provides the ability to create virtual Python environments that do not interfere with either each other, or the main Python installation. If you install virtualenv before you begin coding then you can get into the habit of using it to create completely clean Python environments for each project. This is particularly important for Web development, where each framework and application will have many dependencies.

To set up a new Python environment, change the working directory to wherever you want to store the environment, and run the virtualenv utility in your project’s directory

### VirtualEnv Wrapper

VirtualEnv is much easier to use in conjunction with [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper-win).

To install run the following:
```
> pip install virtualenvwrapper-win
```

Next, you'll want to add an environment variable `WORKON_HOME` to specify the path to store environments. By default, this is `%USERPROFILE%\Envs`.


**Main Commands**
```
> mkvirtualenv <name>
```
Create a new virtualenv environment named `<name>`. The environment will be created in `WORKON_HOME`.
```
> lsvirtualenv
```
List all of the enviornments stored in `WORKON_HOME`.
```
> rmvirtualenv <name>
```
Remove the environment `<name>`. Uses folder_delete.bat.
```
> workon <name>
```
If `<name>` is specified, activate the environment named `<name>` (change the working virtualenv to `<name>`). If a project directory has been defined, we will change into it. If no argument is specified, list the available environments.
```
> deactivate
```
Deactivate the working virtualenv and switch back to the default system Python.

- - -
Sourced From:
http://docs.python-guide.org/en/latest/starting/install/win/
https://pypi.python.org/pypi/virtualenvwrapper-win
