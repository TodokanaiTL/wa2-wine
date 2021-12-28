Mount the game disks in ``/tmp`` (assuming you have them in ``$HOME``):

.. sourcecode:: sh

   mkdir -p /tmp/disk{1..2}
   sudo mount "$HOME/WHITE_ALBUM2_1.iso" /tmp/disk1
   sudo mount "$HOME/WHITE_ALBUM2_2.iso" /tmp/disk2 

Then, mount them in the wineprefix:

.. sourcecode:: sh

   cd "$WINEPREFIX/dosdevices"
   ln -s /tmp/disk1 x:
   ln -s /tmp/disk2 y:
   ln -s "$HOME/WHITE_ALBUM2_1.iso" x::
   ln -s "$HOME/WHITE_ALBUM2_2.iso" y::

Finally, run the setup:

.. sourcecode:: sh

   cd x:
   LANG=ja_JP.utf8 wine setup.exe

.. MacOS

Mount the disks by double clicking them. Then, mount them
in the wineprefix (assuming you have them in your home folder):

.. sourcecode:: sh

   cd "$WINEPREFIX/dosdevices"
   ln -s /Volumes/WHITE_ALBUM2_1 x:
   ln -s /Volumes/WHITE_ALBUM2_2 y:
   ln -s "$HOME/WHITE_ALBUM2_1.iso" x::
   ln -s "$HOME/WHITE_ALBUM2_2.iso" y::

Finally, run the setup:

.. sourcecode:: sh

   cd /Volumes/WHITE_ALBUM2_1
   LC_MESSAGES=ja_JP.UTF-8 wine setup.exe

*Some glyphs may show up as squares.*

