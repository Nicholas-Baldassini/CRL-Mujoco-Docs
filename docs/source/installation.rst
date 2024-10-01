Installation
=====

.. _installation:

Installation Instructions
------------

First, clone the github repository `here <https://crl.utm.utoronto.ca/>`_ then ``cd`` into the cloned directory.
Then, follow the system specific instructions.

You will need ``python >=3.12`` to use the Tkinter GUI library. If you use an earlier version, some features may not work.

System Specific Instructions
------------

**Linux**

.. code-block:: console

    sudo apt install python3-tk
    virtualenv mujEnv
    source ./mujEnv/bin/activate
    pip install -r requirements.txt

**MacOS**

Depending on your system version of ``python`` you may need to install the ``homebrew`` package manager 
and run ``brew install python-tk`` before compiling a new python version. ``homebrew`` is a package manager for MacOS
similar to ``apt`` or ``snap`` package managers on Linux.

*Recommended Steps*

Step 1. 

Install ``homebrew`` with the command found at https://brew.sh/ website. It will look something like,

.. code-block:: console

    /bin/bash -c "$(curl -fsSL https://...)"

Paste the command found on the website.

Step 2. 

Update ``homebrew``

.. code-block:: console

    brew update

Step 3. 

Install ``pyenv`` and ``python-tk``

.. code-block:: console
    
    brew install pyenv python-tk

Step 4.

Install a newer version of ``python``

.. code-block:: console
    
    pyenv install python 3.12

Step 5.

Find where ``pyenv`` installed your ``python`` version,

.. code-block:: console
    
    pyenv root
    /Users/Username/.pyenv

The line ``/Users/Username/.pyenv`` will likely be different on your machine.

Step 6.

Install and create your virtualenv

.. code-block:: console

   /Users/Username/.pyenv/versions/3.12.6/bin/python -m pip install virtualenv
   /Users/Username/.pyenv/versions/3.12.6/bin/python -m virtualenv mujEnv
   source mujEnv/bin/activate
   pip install -r requirements.txt
    

**Windows**

.. code-block:: console

    test 55


Known Versions
------------

If you were able to sucessfuly install the application using the methods listed above, you may ignore this section.

This section is dedicated to documenting known versions this application has been tested to work on. If for example
in the future, version updates cause compatibility errors, you may downgrade to the versions listed below and have a better
chance of getting your application to work.

**Linux Known Versions**

.. code-block:: console

    Python 3.12.6
    pip 24.2
    Kali 2024.3 (Should work on any Similar Debian OS)


and ``pip freeze``

.. code-block:: console

    absl-py==2.1.0
    etils==1.9.4
    fsspec==2024.9.0
    glfw==2.7.0
    importlib_resources==6.4.5
    mujoco==3.2.3
    numpy==2.1.1
    opencv-python==4.10.0.84
    opencv-python-headless==4.10.0.84
    PyOpenGL==3.1.7
    PyQt6==6.7.1
    PyQt6-Qt6==6.7.2
    PyQt6_sip==13.8.0
    typing_extensions==4.12.2
    zipp==3.20.2


**MacOS Known Versions**

.. code-block:: console

    Python 3.12.6
    pip 24.2
    macOS Sequoia 15.0


and ``pip freeze``

.. code-block:: console
    
    absl-py==2.1.0
    etils==1.9.4
    fsspec==2024.9.0
    glfw==2.7.0
    importlib_resources==6.4.5
    mujoco==3.2.3
    numpy==2.1.1
    opencv-python==4.10.0.84
    opencv-python-headless==4.10.0.84
    PyOpenGL==3.1.7
    PyQt6==6.7.1
    PyQt6-Qt6==6.7.3
    PyQt6_sip==13.8.0
    typing_extensions==4.12.2
    zipp==3.20.2


**Windows Known Versions**






