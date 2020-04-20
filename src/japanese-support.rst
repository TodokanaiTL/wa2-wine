Enable Japanese support
^^^^^^^^^^^^^^^^^^^^^^^

.. tabs::

   .. group-tab:: Ubuntu

      .. include:: _include/locale.rst
         :end-before: MacOS

      If not, generate the locale and install some fonts:

      .. sourcecode:: sh

         sudo locale-gen ja_JP.{UTF-8,EUC-JP}
         sudo apt install -y fonts-{takao,mona,monapo}

   .. group-tab:: Arch

      .. include:: _include/locale.rst
         :end-before: MacOS

      If not, generate the locale and install some fonts:

      .. sourcecode:: sh

         sudo locale-gen ja_JP.{UTF-8,EUC-JP}
         sudo pacman -S otf-ipafont ttf-hanazono

   .. group-tab:: Fedora

      .. include:: _include/locale.rst
         :end-before: MacOS

      If not, install the locale and fonts:

      .. sourcecode:: sh

         sudo dnf groupinstall -y 'Japanese Support'
         sudo dnf install -y hanazono-fonts mona-*-fonts

   .. group-tab:: MacOS

      .. include:: _include/locale.rst
         :start-after: MacOS

      | Japanese fonts should also be preinstalled but,
         alas, they don't seem to work 100% in wine.
      | You could, however, install more fonts in
         hopes of getting one to work properly.
