.. sourcecode:: sh

   export WINEARCH=win32
   export WINEPREFIX="$HOME/.local/share/wineprefixes/wa2"
   mkdir -p "$WINEPREFIX" && wineboot -u

Then, install the requirements:

.. sourcecode:: sh

   winetricks lucida corefonts cjkfonts # English & Japanese fonts
   winetricks dxvk # D3D9 to Vulkan translation layer

