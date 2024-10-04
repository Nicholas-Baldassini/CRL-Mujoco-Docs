Simulation Settings
=====
.. _simSettings:

**Lock Robot in Place**
~~~~~~~~~~

Enabling this will lock the base of the robot in place. The robot will still be free to
actuate and move its backbone but it will not be able to slide or translate its base. 

**No. of Links**
~~~~~~~~~~

Specify the number of rigid links making up your robot. Each link is connected by a universal joint 
to the link in front, and behind it.
See the :ref:`Robot Simulation Model<rigid_link_model>` page to better understand this setting.

**Link Length**
~~~~~~~~~~

The length of the rigid links making up the robot.

**Radius**
~~~~~~~~~~


The radius of each rigid link. 

Ex. ``Radius: 0.140``

.. image:: ./media/simSettingsMedia/LargeRadius.png
  :alt: Large Radius robot

``Radius: 0.035`` (Default value)

.. image:: ./media/simSettingsMedia/SmallRadius.png
  :alt: Small radius robot

.. figure:: ./media/simSettingsMedia/SmallRadius.png

   This is the caption of the figure.

**No. of Segments**
~~~~~~~~~~

Number of segments making up the robot. Each segment actuates independently to the other segments. There can only be 1-6 segments.
Each segment can actuate in 2 degrees of freedom. 

.. image:: ./media/2Segment.png
  :alt: Small radius robot


.. note::

Two segment robot with each segment actuated in opposite directions

**Disable Gravity**
~~~~~~~~~~

Toggles gravity. Gravity is a 3 vector set at (0, 0, -9.81)

**Disable Obstacles**
~~~~~~~~~~

Toggles all obstacles. Useful if you want to temporarily disable your obstacles but not delete or change your taskspace file.

**Disable Floor Plane**
~~~~~~~~~~

Removes the floor plane. 

**Colour Scheme**
~~~~~~~~~~
Different colour scheme of the simulation.

.. image:: ./media/simSettingsMedia/Clean.png
  :alt: Clean version

.. image:: ./media/simSettingsMedia/Cinematic.png
  :alt: Cinematic Version

**Shape of Links**
~~~~~~~~~~

**Taskspace filename**
~~~~~~~~~~
