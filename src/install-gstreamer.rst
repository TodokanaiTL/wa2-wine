Install 32-bit GStreamer
^^^^^^^^^^^^^^^^^^^^^^^^

.. tabs::

   .. group-tab:: Ubuntu

      The videos require the good & ugly 32-bit GStreamer plugins to work.

      .. sourcecode:: sh

         sudo apt install -y gstreamer1.0-plugins-{good,ugly}:i386

      You can also open the ``*0.pak`` files in your media player.

   .. group-tab:: Arch

      The videos require the good & ugly 32-bit GStreamer plugins to work.

      The ugly plugins are available in the `chaotic-aur`_ repository.

      .. sourcecode:: sh

         sudo pacman -S lib32-gst-plugins-{good,ugly}

      You can also open the ``*0.pak`` files in your media player.

      .. _chaotic-aur:
         https://wiki.archlinux.org/index.php/Unofficial_user_repositories#chaotic-aur

   .. group-tab:: Fedora

      The videos require the good & ugly 32-bit GStreamer plugins to work.

      .. sourcecode:: sh

         sudo dnf install -y gstreamer1-plugins-{good,ugly}.i686

      You can also open the ``*0.pak`` files in your media player.

   .. group-tab:: MacOS

      Supposedly__, you can install Quicktime instead of GStreamer.

      You can also open the ``*0.pak`` files in your media player.

      If you have more info, please submit a pull request.

      __ https://www.winehq.org/pipermail/wine-users/2011-January/084599.html
