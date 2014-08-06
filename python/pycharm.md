# PyCharm


## Download
[Download PyCharm](http://www.jetbrains.com/pycharm/)
* You want the Free Community Edition.

## Virtualenv Support

##### Using virtualenv and PyCharm
The instructions above are specific to using virtualenv when running Python from the command line. You can also use your virtual environments when running and debugging Python code from within PyCharm. First you have to add your virtual environments to PyCharm's list of Python interpreters:

1. Open the Preferences (Settings on Windows) dialog and choose Project Interpreter.
2. Click on the Configure Interpreters link, which will open up the Python Interpreters dialog. Here you will see all of the interpreters currently configured for PyCharm.
3. Click the + button at the bottom of the list and choose the path to the interpreter in your virtual environment. In my experience sometimes PyCharm is able to find and list these automatically, and other times you have to choose the Local... item and browse for the path yourself. After choosing the path PyCharm will do some setup, displaying a progress indicator and will finally ask you whether you want to set this interpreter as Project Interpreter? Generally you are adding an interpreter precisely because you do want to set it as the interpreter for the current project, in which case you would answer Yes.
4. Your interpreter will now appear in the list of Python interpreters.


If ever you want to change the interpreter for a given project just access the Project Interpreter dialog again and simply select a different interpreter from the Project Interpreter select list. This option is even available to be changed for individual run configurations, as described in the previous post on Setting Up PyCharm to Run MozWebQA Tests:

1. Type ctrl + alt + R to open the Run configuration selector.
2. Type 0, or choose the first option (Edit configurations...) from the select list.
3. In the Run dialog, beside Interpreter > Python Interpreter, choose your interpreter from the list.
4. Click Run.

- - -
Sourced From:
http://www.silverwareconsulting.com/index.cfm/2012/7/24/Getting-Started-with-virtualenv-and-virtualenvwrapper-in-Python
