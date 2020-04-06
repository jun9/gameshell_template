Python Arcade Game Template For GameShell
=========================================

.. image:: doc/screenshot.png

These are instructions on how to get a Python game using the Arcade_ library
working with the GameShell_.

Quick overview:

* Install Python 3.6 (No need, 3.7 pre-installed)
* Install the Arcade library (No need manually, do it in install.sh)
* Clone the game from GitHub
* Install link to menu
* Reload UI

Install Python 3.6 (No need any more)
------------------

GameShell runs on Debian Linux. Right now, GameShell OS 5.0 uses Python 3.7, and Arcade
requires > 3.6. So no need to install 3.6.


Install Arcade (Included in install.sh)
--------------

Now that we have Python 3.7, we need to install the Arcade library. We can do that with:
Unfortunately, last GameShell OS compatible arcade library version is 1.3.4, plus the required pyglet version must be before 1.3.3
The following step is done in the install.sh in the next step, no need to do it manually.

.. code-block:: bash

    pip3 install arcade==1.3.4 pyglet==1.3.3
    

Clone Game
----------

Now clone/grab the code from GitHub:

.. code-block:: bash

    mkdir -p ~/launcher/Menu/GameShell/54_PyGames
    cd ~/launcher/Menu/GameShell/54_PyGames
    git clone https://github.com/jun9/gameshell_template.git .


Install the Game
----------------

Now we have the code installed, but there is not a link to it from the menu.
Run this command to copy over the link:

.. code-block:: bash

    cd ~/launcher/Menu/GameShell/54_PyGames
    sh ./install.sh

Refresh menu
------

We installed the link. Use Reload UI menu to reload UI. No reboot needed.




.. _GameShell: https://www.clockworkpi.com/
.. _Arcade: http://arcade.academy/
