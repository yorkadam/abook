# Address Book Python 3.4 Desktop Application

This application is a Python 3.4 Tkinter based desktop application running as a
stand alone application. Written using PyCharm on Debian 8 Jessie this application
works best on Linux systems. However, I did test on Windows 7 and Windows 10 and
the application runs but windowing would need adjustments. Users wanting to run
this application on windows would need to tweak the tkinter window settings and
make other minor visual adjustments.

## On PyPi
Deployed on PyPi makes this application easy to install. However, being new
to PyPi I did not properly configure some of the packaging on PyPi which causes
some minor issues that can be worked around until I have time to fix it.

### PyPi Install
Installing using pip assumes you have Python 3.4 installed that includes the
tkinter libraries.

To install: pip install addressbook (or pip3.4 install addressbook)
To Run: Navigate to the "Site-Packages" folder for your python install and
run using main.py

#### Example
cd: /usr/local/lib/python3.4/site-packages/addressbook
python3.4 main.py (or python main.py if your default python is already 3.4)

### Alternate Install
Simply copy / clone the repository and run main.py.

# Alternate Versions
On GitHub I've been working on a web-based version by converting the desktop version
to a web interface.

Please see https://github.com/yorkadam/addressweb for the details on this alternate
version.

# End User Directions
Detailed user directions on how the application is used can be found at:
https://adamyork.com/projects/address-book/

Additionally, the "Help" menu found at the top of the running application window
also includes detailed usage instructions.

Users not wanting to leave the GitHub website to see the directions; may review:
help.py [ abook/addressbook/help.py ]

# Developers
I did not produce any developer documentation as this project was mostly intended
for personal usage as opposed to a community project.  However, the main components
which developers would need to know to work with code are:

1. Tkinter (tkinter) / Tk
2. Object Oriented Programming (ooo) using Python classes as objects / models.
3. SQLite
4. SQL query language (SQLite dialect)

## Known Issues
Already mentioned, install via PyPi is not totally correct use the work-around
to install using pip.  Also, Tkinter (tkinter) is not always installed with
some distributions of Python causing a "no module named _tkinter" error.
If that happens just create a virtual environment with a version of python that
includes Tk.

Windowing is not correct on Microsoft Windows OS and needs to be tweaked.

When cloning this repository to use with PyCharm you may run into PyCharm issues
if your version of PyCharm is different than mine. I'm using PyCharm 5.0.1.

# RaspberryPi
This application runs very well on RaspberryPi using a Debian based distribution.
I tested on RaspberryPi (original B model) using the Raspbian image at:
https://www.raspberrypi.org/downloads/














