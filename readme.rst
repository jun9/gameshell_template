Python Arcade Game Template For GameShell
=========================================

.. image:: doc/screenshot.png

These are instructions on how to get a Python game using the Arcade_ library
working with the GameShell_.

Quick overview:

* Install Python 3.6 (No need, 3.7 pre-installed)
* Install the Arcade library
* Clone the game from GitHub
* Install link to menu
* Restart

Install Python 3.6 (No need any more)
------------------

GameShell runs on Debian Linux. Right now, GameShell OS 5.0 uses Python 3.7, and Arcade
requires > 3.6. So no need to install 3.6.


Install Arcade
--------------

Now that we have Python 3.7, we need to install the Arcade library. Do that with:

.. code-block:: bash

    python3 -m pip install arcade

Clone Game
----------

Now clone/grab the code from GitHub:

.. code-block:: bash

    cd ~/games
    git clone https://github.com/jun9/gameshell_template.git

Install the Game
----------------

Now we have the code installed, but there is not a link to it from the menu.
Run this command to copy over the link:

.. code-block:: bash

    cd ~/games/gameshell_tempate
    chmod u+x install.sh
    ./install.sh

Reboot
------

We installed the link. We need to reboot the device to re-look at the links.

.. code-block:: bash

    sudo reboot

Update The Code
---------------

Something new on GitHub you want to pull down?

You can update the code with:

.. code-block:: bash

    cd ~/games/gameshell_tempate
    git pull

.. _GameShell: https://www.clockworkpi.com/
.. _Arcade: http://arcade.academy/
