Install wine and winetricks
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. tab:: Ubuntu

   Install ``winehq-stable`` following the `official instructions for Ubuntu <https://wiki.winehq.org/Ubuntu>`_.

   .. include:: _include/winetricks.rst

   You might also need to install ``cabextract``:

   .. sourcecode:: sh

      sudo apt install -y cabextract

.. tab:: Arch

   .. warning::

      The game may crash on Wine 7.0 or newer.
      It's recommended to use an older version.

   Install ``wine`` following the `instructions on the Arch wiki <https://wiki.archlinux.org/index.php/Wine#Installation>`_.

   Get the latest version of ``winetricks``:

   .. sourcecode:: sh

      sudo pacman -S winetricks

   You might also need to install ``cabextract``:

   .. sourcecode:: sh

      sudo pacman -S cabextract

.. tab:: Fedora

   Install ``winehq-stable`` following the `official instructions for Fedora <https://wiki.winehq.org/Fedora>`_.

   .. include:: _include/winetricks.rst

   You might also need to install ``cabextract``:

   .. sourcecode:: sh

      sudo dnf install -y cabextract

.. tab:: MacOS

   Install `XQuartz <https://www.xquartz.org/releases/index.html>`_
   and `Wine Staging <https://dl.winehq.org/wine-builds/macosx/download.html>`_.

   .. include:: _include/winetricks.rst
