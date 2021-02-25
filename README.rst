About this project
==================

This is FTP server & client, client using PyQt5 GUI framework

Why I create this project?
--------------------------

Because Qt framework seems a powerful and interesting framework, so I
want to learn and try this framework. Another reason I'm interested
about ``Internet Protocol`` including the FTP Protocol so I want to try
to implement FTP Protocol.

Dependencies
------------

PyQt5.x

Tested on
---------

``python3.8``

Usage
-----

.. code:: bash

    $ python ftp_server.py
    $ python ftp_client.py

    | Note:
    | When you run ftp\_server.py you may need permission because the
    ftp server port default run on 20 & 21, may you can run
    ``sudo python ftp_server.py``

Platform
--------

Currently can only run on Linux like OS e.g Ubuntu, Mac OSX etc.

Screenshots
-----------

ftp server
''''''''''
.. image:: https://gitlab.com/mikeramsey/wizardftp/-/raw/master/screenshots/server.jpg
   :width: 90%
   :align: center

ftp client
''''''''''
.. image:: https://gitlab.com/mikeramsey/wizardftp/-/raw/master/screenshots/client_main_window.png
   :width: 90%
   :align: center


Credits
----------------
Original PyQt4 version which this was based on
https://github.com/jacklam718/ftp

permissions.py source from Perfm
https://github.com/keysemble/perfm/

Humanbytes Filesize function
https://stackoverflow.com/a/63839503/8874388