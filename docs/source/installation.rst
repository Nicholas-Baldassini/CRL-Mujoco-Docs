Installation
=====

.. _installation:

Installation
------------

First, clone the repository `here <https://crl.utm.utoronto.ca/>`_ then ``cd`` into the cloned directory.
Then, follow the system specific instructions.

**Linux**

.. code-block:: console

    virtualenv mujEnv
    source ./mujEnv/bin/activate
    pip install -r requirements.txt

**MacOS**

.. code-block:: console

    python3 -m venv mujEnv
    source mujEnv/bin/activate
    python3 -m pip install -r requirements.txt


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
    
    Python 3.9.6
    pip 21.2.4
    MacOS Sequoia 15.0


and ``pip freeze``

.. code-block:: console

    absl-py==2.1.0
    etils==1.5.2
    fsspec==2024.9.0
    glfw==2.7.0
    importlib_resources==6.4.5
    mujoco==3.2.3
    numpy==2.0.2
    opencv-python==4.10.0.84
    opencv-python-headless==4.10.0.84
    PyOpenGL==3.1.7
    PyQt6==6.7.1
    PyQt6-Qt6==6.7.2
    PyQt6_sip==13.8.0
    typing_extensions==4.12.2
    zipp==3.20.2

**Windows Known Versions**






