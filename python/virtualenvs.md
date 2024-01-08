# python virtual environments

Once you are in the directory where you would like the environments to live, you can create an environment by running the following command:

$ python3 -m venv venv1  (-m calls for module name, than we type venv as a module and venv1 as name for our environment)
or simply:
$ virtualenv venv1 (venv1 is just a name for our environment)

Essentially, this sets up a new directory that contains a few items which we can view with the ls command:

$ ls venv1

> Output
bin include lib lib64 pyvenv.cfg share


Together, these files work to make sure that your projects are isolated from the broader context of your local machine, so that system files and project files don’t mix. This is good practice for version control and to ensure that each of your projects has access to the particular packages that it needs. Python Wheels, a built-package format for Python that can speed up your software production by reducing the number of times you need to compile, will be in the Ubuntu 16.04 share directory.

To use this environment, you need to activate it, which you can do by typing the following command that calls the activate script:

$ source venv1/bin/activate


Your prompt will now be prefixed with the name of your environment, in this case it is called my_env. Your prefix may look somewhat different, but the name of your environment in parentheses should be the first thing you see on your line.

This prefix lets us know that the environment my_env is currently active, meaning that when we create programs here they will use only this particular environment’s settings and packages. 

Note: Within the virtual environment, you can use the command python instead of python3, and pip instead of pip3 if you would prefer. If you use Python 3 on your machine outside of an environment, you will need to use the python3 and pip3 commands exclusively. 

To leave the environment, simply type the command deactivate and you will return to your original directory. 

youtube guides:
https://www.youtube.com/watch?v=UqkT2Ml9beg
https://www.youtube.com/watch?v=SeJvz-ngCnk

TLDR:

$ virtualenv venv1 (create venv1 environment)
$ source venv1/bin/activate (activates venv1 environment)
$ deactivate (deactivates venv1)

<!--- create REQUIREMENTS.txt 
$ pip list # Create a list of installed packages
$ pip freeze # Create a list of dependancy versions
$ pip freeze > requirements.txt # Export it to text file
$ pip install -r requirements.txt # Install by reading from requirements.txt

<!--- install specific version of package (you can use * global sign)
$ python3 -m pip install "package==1.4"
$ pip install "package==1.4"
$ pip install "package==1*" (will install any version starting with 1)

<!--- install greater than or equal to version and less than another:
python3 -m pip install "SomeProject>=1,<2"

<!--- all INFO at official page
https://packaging.python.org/tutorials/installing-packages/





