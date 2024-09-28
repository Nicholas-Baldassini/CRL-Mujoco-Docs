Installation
=====

.. _installation:

Installation
------------

First, clone the repository `here` then
follow the system specific instructions.

**Linux**

.. code-block:: console

   sudo apt install python3-tk libxcb-cursor0 python3-dev build-essential libssl-dev libffi-dev libxml2-dev  libxslt1-dev zlib1g-dev libglew-dev libosmesa6-dev patchelf

**MacOS**

.. code-block:: console

    python3 -m venv mujEnv
    source mujEnv/bin/activate
    python3 -m pip install -r requirements.txt

You may see the following error,


```WARNING: Secure coding is automatically enabled for restorable state! However, not on all supported macOS versions of this application. Opt-in to secure coding explicitly by implementing NSApplicationDelegate.applicationSupportsSecureRestorableState:```

This is a reported bug with the Tkiner package. Dont worry about it.

**Windows**

.. code-block:: console
    
    test 55

.. toctree::

   usage
   installation
   SimulationSettings



