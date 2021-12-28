Install 32-bit GStreamer
^^^^^^^^^^^^^^^^^^^^^^^^

.. tab:: Ubuntu

   The videos require the good, ugly & libav 32-bit GStreamer plugins to work.

   .. sourcecode:: sh

      sudo apt install -y gstreamer1.0-{plugins-{good,ugly},libav}:i386

   You can also open the ``mv*0.pak`` files in your media player.

.. tab:: Arch

   The videos require the good, ugly & libav 32-bit GStreamer plugins to work.

   The ugly & libav plugins can be installed manually or with an AUR helper like paru_.

   .. sourcecode:: sh

      sudo pacman -S lib32-gst-plugins-good
      paru -S lib32-gst-{plugins-ugly,libav}

   You can also open the ``mv*0.pak`` files in your media player.

   .. _paru: https://github.com/Morganamilo/paru

.. tab:: Fedora

   The videos require the good, ugly & libav 32-bit GStreamer plugins to work.

   .. sourcecode:: sh

      sudo dnf install -y gstreamer1-{plugins-{good,ugly},libav}.i686

   You can also open the ``mv*0.pak`` files in your media player.

.. tab:: MacOS

   Supposedly__, you can install Quicktime instead of GStreamer.

   You can also open the ``mv*0.pak`` files in your media player.

   If you have more info, please submit a pull request.

   __ https://www.winehq.org/pipermail/wine-users/2011-January/084599.html
