Install wine and winetricks
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. tabs::

   .. group-tab:: Ubuntu

      Install ``wine`` following the `official instructions for Ubuntu <https://wiki.winehq.org/Ubuntu>`_.

      .. include:: _include/winetricks.rst

      You might also need to install ``cabextract``:

      .. sourcecode:: sh

         sudo apt install -y cabextract

   .. group-tab:: Arch

      Install ``wine`` following the `instructions on the Arch wiki <https://wiki.archlinux.org/index.php/Wine#Installation>`_.

      .. include:: _include/winetricks.rst

      You might also need to install ``cabextract``:

      .. sourcecode:: sh

         sudo pacman -S cabextract

   .. group-tab:: Fedora

      Install ``wine`` following the `official instructions for Fedora <https://wiki.winehq.org/Fedora>`_.

      .. include:: _include/winetricks.rst

      You might also need to install ``cabextract``:

      .. sourcecode:: sh

         sudo dnf install -y cabextract

   .. group-tab:: MacOS

      Install `XQuartz 2.7.9 <https://www.xquartz.org/releases/XQuartz-2.7.9.html>`_ (newer releases have font issues).

      Download `wine <https://dl.winehq.org/wine-builds/macosx/download.html>`_ (any version you want) and run the installer.

      .. include:: _include/winetricks.rst
