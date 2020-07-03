Install & patch White Album 2 on wine
-------------------------------------

.. toctree::
   :maxdepth: 1

   japanese-support.rst
   install-wine.rst
   install-gstreamer.rst
   setup-wineprefix.rst
   install-game.rst
   install-patch.rst

.. raw:: html

   <hr>

.. container::

   | You should now be able to launch the game with wine:
   | (assuming it's installed in ``$WINEPREFIX/drive_c/Program Files/WHITE ALBUM2``)

   .. sourcecode:: sh

      wine 'C:\Program Files\WHITE ALBUM2\WA2_en.exe'

   Do not forget to set ``WINEPREFIX="$HOME/.local/share/wineprefixes/wa2"``
   whenever you launch the game in the future.

   If you need help, check the `issues <https://github.com/TodokanaiTL/wa2-wine/issues>`_
   and submit a new one if your issue doesn't already exist.

Links
^^^^^

* `Wine AppDB Entry <https://appdb.winehq.org/objectManager.php?sClass=version&iId=29024>`_
* `Todokanai TL Website <https://todokanaitl.github.io/>`_
* `Todokanai TL Discord <https://discord.gg/5rrxEUN>`_
* `Patch Issue Tracker <https://github.com/TodokanaiTL/WA2EnglishPatch/issues>`_

Credits
^^^^^^^

* https://forum.ubuntu.com.cn/viewtopic.php?p=3108761#p3108761
* https://ubuntuforums.org/showthread.php?t=383628
* https://forums.fedoraforum.org/showthread.php?315330-Install-Language-Packs
* https://wiki.winehq.org/MacOS_FAQ#How_can_I_switch_the_locale.3F
